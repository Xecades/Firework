<template>
    <div id="click" @click="start">
        <div id="breathe"></div>
    </div>
    <div id="card"></div>
    <div id="firework"></div>
    <div id="svgs">
        <svg id="svg1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 226.62 144.94" style="display: none">
            <path d="M73.13,9.5A21.13,21.13 0 0 169,13.5A13,13 0 0 163.71,15.59C60.059999999999995,16.11 56.78,14.66 57.58,9.59C58.379999999999995,4.52 65.1,2.09 66.8,2C68.5,1.9100000000000001 71.44999999999999,1.83 76.6,5C81.75,8.17 89.52,3.19 92.28,.36C89.84,2.81 84,7.080000000000002 79.92,10.88C75.84,14.68 56.37,37.45 53.69,39.82C51.01,42.19 47.65,46.26 42.58,46.72C37.669999999999995,47.16 41.8,41.42999999999999 46.8,37.16C50.93,33.65 63.64,26.679999999999996 74.75,24.06C85.86,21.44 92.94999999999999,19 99.52,14C106.09,9 111.21999999999998,4.030000000000001 110.07,1.3100000000000005C108.92,-1.4100000000000001 102,2.99 95,9.31C88,15.63 73.13000000000001,33.14 68.62,40.97C64.11,48.8 74.27,47.33 80.11,41.8"/>
            <path d="M98.37,34.34s5.3-6.64,2.36-8.24S90.2,29.48,87,32.29s-9,9.39-6.4,13.7c1.64,2.69,8.1-1.68,12.72-5.91A38,38,0,0,0,98.37,34.34Z"/>
            <path d="M105.71,26S95.62,39.29,94.31,41.93c-1.38,2.81-.67,3.64.29,4.34,1.77,1.3,10.25-4.67,10.6-5"/>
            <line x1="116.75" y1="26.04" x2="88.03" y2="64.8"/>
            <path d="M105.2,41.23s10.59-11.43,16.72-14.3,9-1.54,1.34,8-7.48,10.68-5.87,11.36c3.14,1.09,11.87-5.1,13.91-7.21"/>
            <line x1="141.26" y1="26.04" x2="112.03" y2="64.8"/>
            <path d="M130.47,39.82s13.34-14.14,20.17-14S147.2,35.42,146,36.63s-7,7.09-5,9.58,14.11-6.45,14.81-7.09"/>
            <path d="M165.77,26s-11.91,15.34-12.68,16.78-1.11,2.79.51,4,10.47-3.23,18.55-12.68A79.46,79.46,0,0,0,179,26s-28.74,43.09-36.8,37.34,33.49-19.86,38.64-25.91"/>
            <path d="M3.31,123.1s-4.25,2.13-2.3,4.64,8.77.3,14.69-7.19,25.05-34.19,32.22-38c-3.25,6.44-14.1,42.69-17.48,46.19,3.51-3.46,30.09-41.39,33.38-43.8s5.88-1.4,6.26-.51.25,2.24-1.79,3.77"/>
            <path d="M44.62,118.76s12.22-.64,17.86-8c3.33-4.33-1.54-3.72-6.86-1.06A39.24,39.24,0,0,0,47,116c-3,3.11-8.2,8.84-4.62,12.35s20.49-7.88,22.4-9.91"/>
            <path d="M72.7,108.1s-11.56,13-11.81,18.9,11.68-.64,26-18.9c-8.62,11.69-16.34,20.47-9.57,21s14.23-11.6,18-16.71S95,108.55,94,110.85s-4.65,10.81,4.66,7.8"/>
            <path d="M139.54,87.32s-2.89,9.93-14.89,13.25-8.1-10.66,2.17-14.93,26.56-2.56,16.41,9.89-23.45,22.67-18,26c7.21,3.32,42.38-29,49.59-38.19,0,0-25,26.25-28.79,31.49-2.42,3.51-15,21.83-26,27.63s-11.61-2.5-5.61-6.63,10.46-5.43,18.06-7.34,19.47-7,23.23-10.29"/>
            <path d="M154.55,118.93s7.44.34,15.36-6.1-2-6.94-9.7.42-10.09,10-8.3,14.73,14.87-3.73,19.59-7.3"/>
            <path d="M188.42,116.53s6.17-7.19,1.79-8.07-9.58,3.22-12.51,5.77-11,10.21-7,14.11S188.42,116.53,188.42,116.53Z"/>
            <path d="M196,108.1s-13.59,16.54-12.09,19.47,10.18-3.7,12.73-5.74"/>
            <path d="M207.44,108.1s-17.95,22.44-16,20.66c4-6.36,23.4-19.86,25.59-20.09,1.22-1.14-8.17,6.71,0,6.14"/>
        </svg>
        <svg id="svg2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 226.62 144.94" style="display: none">
            <path d="M73.13,9.5A21.13,21.13 0 0 169,13.5A13,13 0 0 163.71,15.59C60.059999999999995,16.11 56.78,14.66 57.58,9.59C58.379999999999995,4.52 65.1,2.09 66.8,2C68.5,1.9100000000000001 71.44999999999999,1.83 76.6,5C81.75,8.17 89.52,3.19 92.28,.36C89.84,2.81 84,7.080000000000002 79.92,10.88C75.84,14.68 56.37,37.45 53.69,39.82C51.01,42.19 47.65,46.26 42.58,46.72C37.669999999999995,47.16 41.8,41.42999999999999 46.8,37.16C50.93,33.65 63.64,26.679999999999996 74.75,24.06C85.86,21.44 92.94999999999999,19 99.52,14C106.09,9 111.21999999999998,4.030000000000001 110.07,1.3100000000000005C108.92,-1.4100000000000001 102,2.99 95,9.31C88,15.63 73.13000000000001,33.14 68.62,40.97C64.11,48.8 74.27,47.33 80.11,41.8"/>
            <path d="M98.37,34.34s5.3-6.64,2.36-8.24S90.2,29.48,87,32.29s-9,9.39-6.4,13.7c1.64,2.69,8.1-1.68,12.72-5.91A38,38,0,0,0,98.37,34.34Z"/>
            <path d="M105.71,26S95.62,39.29,94.31,41.93c-1.38,2.81-.67,3.64.29,4.34,1.77,1.3,10.25-4.67,10.6-5"/>
            <line x1="116.75" y1="26.04" x2="88.03" y2="64.8"/>
            <path d="M105.2,41.23s10.59-11.43,16.72-14.3,9-1.54,1.34,8-7.48,10.68-5.87,11.36c3.14,1.09,11.87-5.1,13.91-7.21"/>
            <line x1="141.26" y1="26.04" x2="112.03" y2="64.8"/>
            <path d="M130.47,39.82s13.34-14.14,20.17-14S147.2,35.42,146,36.63s-7,7.09-5,9.58,14.11-6.45,14.81-7.09"/>
            <path d="M165.77,26s-11.91,15.34-12.68,16.78-1.11,2.79.51,4,10.47-3.23,18.55-12.68A79.46,79.46,0,0,0,179,26s-28.74,43.09-36.8,37.34,33.49-19.86,38.64-25.91"/>
            <path d="M3.31,123.1s-4.25,2.13-2.3,4.64,8.77.3,14.69-7.19,25.05-34.19,32.22-38c-3.25,6.44-14.1,42.69-17.48,46.19,3.51-3.46,30.09-41.39,33.38-43.8s5.88-1.4,6.26-.51.25,2.24-1.79,3.77"/>
            <path d="M44.62,118.76s12.22-.64,17.86-8c3.33-4.33-1.54-3.72-6.86-1.06A39.24,39.24,0,0,0,47,116c-3,3.11-8.2,8.84-4.62,12.35s20.49-7.88,22.4-9.91"/>
            <path d="M72.7,108.1s-11.56,13-11.81,18.9,11.68-.64,26-18.9c-8.62,11.69-16.34,20.47-9.57,21s14.23-11.6,18-16.71S95,108.55,94,110.85s-4.65,10.81,4.66,7.8"/>
            <path d="M139.54,87.32s-2.89,9.93-14.89,13.25-8.1-10.66,2.17-14.93,26.56-2.56,16.41,9.89-23.45,22.67-18,26c7.21,3.32,42.38-29,49.59-38.19,0,0-25,26.25-28.79,31.49-2.42,3.51-15,21.83-26,27.63s-11.61-2.5-5.61-6.63,10.46-5.43,18.06-7.34,19.47-7,23.23-10.29"/>
            <path d="M154.55,118.93s7.44.34,15.36-6.1-2-6.94-9.7.42-10.09,10-8.3,14.73,14.87-3.73,19.59-7.3"/>
            <path d="M188.42,116.53s6.17-7.19,1.79-8.07-9.58,3.22-12.51,5.77-11,10.21-7,14.11S188.42,116.53,188.42,116.53Z"/>
            <path d="M196,108.1s-13.59,16.54-12.09,19.47,10.18-3.7,12.73-5.74"/>
            <path d="M207.44,108.1s-17.95,22.44-16,20.66c4-6.36,23.4-19.86,25.59-20.09,1.22-1.14-8.17,6.71,0,6.14"/>
        </svg>
        <svg id="svg3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 226.62 144.94" style="display: none">
            <path d="M73.13,9.5A21.13,21.13 0 0 169,13.5A13,13 0 0 163.71,15.59C60.059999999999995,16.11 56.78,14.66 57.58,9.59C58.379999999999995,4.52 65.1,2.09 66.8,2C68.5,1.9100000000000001 71.44999999999999,1.83 76.6,5C81.75,8.17 89.52,3.19 92.28,.36C89.84,2.81 84,7.080000000000002 79.92,10.88C75.84,14.68 56.37,37.45 53.69,39.82C51.01,42.19 47.65,46.26 42.58,46.72C37.669999999999995,47.16 41.8,41.42999999999999 46.8,37.16C50.93,33.65 63.64,26.679999999999996 74.75,24.06C85.86,21.44 92.94999999999999,19 99.52,14C106.09,9 111.21999999999998,4.030000000000001 110.07,1.3100000000000005C108.92,-1.4100000000000001 102,2.99 95,9.31C88,15.63 73.13000000000001,33.14 68.62,40.97C64.11,48.8 74.27,47.33 80.11,41.8"/>
            <path d="M98.37,34.34s5.3-6.64,2.36-8.24S90.2,29.48,87,32.29s-9,9.39-6.4,13.7c1.64,2.69,8.1-1.68,12.72-5.91A38,38,0,0,0,98.37,34.34Z"/>
            <path d="M105.71,26S95.62,39.29,94.31,41.93c-1.38,2.81-.67,3.64.29,4.34,1.77,1.3,10.25-4.67,10.6-5"/>
            <line x1="116.75" y1="26.04" x2="88.03" y2="64.8"/>
            <path d="M105.2,41.23s10.59-11.43,16.72-14.3,9-1.54,1.34,8-7.48,10.68-5.87,11.36c3.14,1.09,11.87-5.1,13.91-7.21"/>
            <line x1="141.26" y1="26.04" x2="112.03" y2="64.8"/>
            <path d="M130.47,39.82s13.34-14.14,20.17-14S147.2,35.42,146,36.63s-7,7.09-5,9.58,14.11-6.45,14.81-7.09"/>
            <path d="M165.77,26s-11.91,15.34-12.68,16.78-1.11,2.79.51,4,10.47-3.23,18.55-12.68A79.46,79.46,0,0,0,179,26s-28.74,43.09-36.8,37.34,33.49-19.86,38.64-25.91"/>
            <path d="M3.31,123.1s-4.25,2.13-2.3,4.64,8.77.3,14.69-7.19,25.05-34.19,32.22-38c-3.25,6.44-14.1,42.69-17.48,46.19,3.51-3.46,30.09-41.39,33.38-43.8s5.88-1.4,6.26-.51.25,2.24-1.79,3.77"/>
            <path d="M44.62,118.76s12.22-.64,17.86-8c3.33-4.33-1.54-3.72-6.86-1.06A39.24,39.24,0,0,0,47,116c-3,3.11-8.2,8.84-4.62,12.35s20.49-7.88,22.4-9.91"/>
            <path d="M72.7,108.1s-11.56,13-11.81,18.9,11.68-.64,26-18.9c-8.62,11.69-16.34,20.47-9.57,21s14.23-11.6,18-16.71S95,108.55,94,110.85s-4.65,10.81,4.66,7.8"/>
            <path d="M139.54,87.32s-2.89,9.93-14.89,13.25-8.1-10.66,2.17-14.93,26.56-2.56,16.41,9.89-23.45,22.67-18,26c7.21,3.32,42.38-29,49.59-38.19,0,0-25,26.25-28.79,31.49-2.42,3.51-15,21.83-26,27.63s-11.61-2.5-5.61-6.63,10.46-5.43,18.06-7.34,19.47-7,23.23-10.29"/>
            <path d="M154.55,118.93s7.44.34,15.36-6.1-2-6.94-9.7.42-10.09,10-8.3,14.73,14.87-3.73,19.59-7.3"/>
            <path d="M188.42,116.53s6.17-7.19,1.79-8.07-9.58,3.22-12.51,5.77-11,10.21-7,14.11S188.42,116.53,188.42,116.53Z"/>
            <path d="M196,108.1s-13.59,16.54-12.09,19.47,10.18-3.7,12.73-5.74"/>
            <path d="M207.44,108.1s-17.95,22.44-16,20.66c4-6.36,23.4-19.86,25.59-20.09,1.22-1.14-8.17,6.71,0,6.14"/>
        </svg>
        <svg id="edge1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 226.62 144.94" style="display: none">
            <polyline points="16.95 4.36 1.5 4.36 1.5 14.76"/>
            <polyline points="210.67 143.44 226.13 143.44 226.13 133.04"/>
        </svg>
        <svg id="edge2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 226.62 144.94" style="display: none">
            <polyline points="16.95 4.36 1.5 4.36 1.5 14.76"/>
            <polyline points="210.67 143.44 226.13 143.44 226.13 133.04"/>
        </svg>
        <svg id="edge3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 226.62 144.94" style="display: none">
            <polyline points="16.95 4.36 1.5 4.36 1.5 14.76"/>
            <polyline points="210.67 143.44 226.13 143.44 226.13 133.04"/>
        </svg>
    </div>
</template>

<script>
import Vivus from "vivus";
import { Fireworks } from "fireworks-js";

export default {
    name: "App",
    data() {
        return { f: true }
    },
    methods: {
        start() {
            if (this.f == false) return;
            this.f = false;
            console.log("launch");
            const clicker = document.querySelector("#click");
            clicker.style["opacity"] = "0";
            const container = document.querySelector("#firework");
            const fireworks = new Fireworks(container, { sound: { enabled: false }, intensity: 20 });
            fireworks.start();
            setTimeout(() => {
                let svgObj = { duration: 400, type: "oneByOne", pathTimingFunction: Vivus.EASE };
                let edgeObj = { duration: 40, type: "sync", pathTimingFunction: Vivus.EASE };
                for (let i = 1; i <= 3; i++) {
                    document.querySelector(`#svg${i}`).style["display"] = "unset";
                    new Vivus(`svg${i}`, svgObj, () => {
                        new Vivus(`edge${i}`, edgeObj, () => {
                            setTimeout(() => {
                                const card = document.querySelector("#card");
                                card.style["opacity"] = ".14";
                                card.style["box-shadow"] = "#eee 0px 1px 90px";
                            }, 200);
                        });
                        document.querySelector(`#edge${i}`).style["display"] = "unset";
                    });
                }
            }, 2000);
        }
    },
    mounted() {
        document.onkeydown = () => { this.start(); };
    },
};
</script>

<style lang="stylus">
    #click
        z-index: 10086;
        line-height: 100vh;
        height: 100vh;
        width: 100vw;
        position: fixed;
        display: block;
        transition: opacity 1s;
    
     #breathe
        left: calc(50vw - 25px);
        top: calc(40vh);
        position: fixed
        width: 50px;
        height: 50px;
        border: 1px solid #fff;
        border-radius: 50%;
        cursor: pointer;
        box-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);
        animation-timing-function: ease-in-out;
        animation-name: breathe;
        animation-duration: 1500ms;
        animation-iteration-count: infinite;
        animation-direction: alternate;

    @keyframes breathe
        0%
            opacity: .4;
            box-shadow: 0 1px 2px rgba(255, 255, 255, 0.4), 0 1px 1px rgba(255, 255, 255, 0.2) inset;
            transform: scale(1);

        100%
            opacity: 1;
            border: 1px solid rgba(255, 255, 255, 0.7);
            box-shadow: 0 1px 20px #fff, 0 1px 10px #fff inset;
            transform: scale(1.1);

    #firework
        width: 100%;
        height: 100%;
        position: fixed;

    #card
        display: inline-block;
        width: 48vw;
        height: 32vw;
        left: calc(50vw - 24vw);
        top: calc(50vh - 16vw);
        position: absolute;
        background-color: #eee;
        border-radius: 3px;
        opacity: 0;
        transition: opacity .8s ease-in, box-shadow 2s ease-in;

    #svgs svg
        display: inline-block;
        width: 40vw;
        height: 30vw;
        left: calc(50vw - 20vw);
        top: calc(50vh - 15vw);
        position: absolute;
        stroke-linecap: round;
        stroke-linejoin: round;
        fill: none;
        overflow: visible;
    
    @media (max-width: 768px)
        #svgs svg
            width: 80vw;
            height: 60vw;
            left: calc(50vw - 40vw);
            top: calc(40vh - 35vw);
        #card
            width: 94vw;
            height: 72vw;
            left: calc(50vw - 47vw);
            top: calc(40vh - 42vw);
    
    #svg1, #edge1
        stroke: #ea5514;
        stroke-width: 8.0;
        filter: blur(6px);

    #svg2, #edge2
        stroke: #ea5514;
        stroke-width: 5.0;
    
    #svg3, #edge3
        stroke: #fff;
        stroke-width: 1.5;
</style>