<div class="text-white h-[80vh]">
    <ul class=" pl-7 py-4 list-disc">
        <li>No Virtual DOM; DOM updates at build time for efficient rendering.</li>
        <li>Compiles to highly optimized Vanilla JS for runtime efficiency.</li>
        <li>Small bundle sizes contribute to faster load times.</li>
        <li>Automatic code optimizations for cleaner and performant output.</li>
        <li>SvelteKit extends capabilities for building full-stack applications seamlessly.</li>
    </ul>
</div>
<div class="abs">
    <img src="logo.png" class="absolute inset-0 m-auto h-40 md:h-72 opacity-10" alt="logo">
</div>

<style>
    li{
        margin: 20px 0px 20px 10px;
        font-size: x-large;
    }
    li::marker{
        color: hsl(15,100%,60%);
    }
    .abs{
        background-color: hsl(210, 13%, 10%);
        position: fixed;
        top:0;
        z-index: -1;
        height: 100vh;
        width: 100vw;
    }
</style>