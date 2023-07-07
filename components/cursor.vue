<template>
    <div>
        <div class="logo" style="width: 100px; height: 100px; background: #000"></div>
        <p class="logo">
            <span>
                <label>Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita non et consequatur veritatis nulla
                    eius optio, molestiae perferendis itaque. Magni minima quibusdam autem laborum itaque.</label>
            </span>
        </p>

        <button class="hover" v-hover-direction>
            <span>Hover me</span>
        </button>
    </div>
</template>

<script>
import Vue from "vue";
Vue.directive("hover-direction", {
    inserted(el) {
        el.addEventListener("mousemove", ({ offsetX }) => {
            let side = offsetX > el.clientWidth / 2 ? "right" : "left";
            if (!el.classList.contains("left") && !el.classList.contains("right"))
                el.classList.add(side);
        });

        el.addEventListener("mouseleave", () => {
            el.classList.remove("left");
            el.classList.remove("right");
        });
    }
});
export default {
    mounted() {
        console.log("here");
    }
};
</script>
  
<style>
.hover {
    position: relative;
    width: 100px;
    height: 100px;
    display: flex;
    border: 0;
    outline: 0;
    overflow: hidden;
    border-radius: 50%;
    background-color: #000;
    margin: 100px;
    z-index: 1;
    transition: transform 200ms;
}

.hover:hover {
    transform: scale(1.2);
}

.hover:before {
    position: absolute;
    content: "";
    top: -5px;
    left: -5px;
    right: -5px;
    bottom: -5px;
    z-index: -1;
    background-color: #777;
    transition: transform 300ms;
    backface-visibility: hidden;
}

.hover.right:before {
    transform: translateX(-100%);
}

.hover.left:before {
    transform: translateX(100%);
}

.hover span {
    margin: auto;
    color: #fff;
}
</style>