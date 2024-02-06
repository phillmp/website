<script>
    export let href="void"
</script>
<!-- left -->
<div class="group shadow-[inset_2px_0px_4px_0px_rgba(255,0,0,0.25)] hover:shadow-[inset_2px_0px_4px_0px_rgba(255,0,0,0.25)] rounded-3xl transition-shadow bg-white active:bg-zinc-100">
<!-- right -->
<div class="shadow-[inset_-2px_0px_4px_0px_rgba(15,171,238,0.25)] group-hover:shadow-[inset_-2px_0px_4px_0px_rgba(15,171,238,0.25)] rounded-3xl transition-shadow">
<!-- top -->
<div class="shadow-[-2px_-2px_4px_0px_rgba(255,245,0,0.5)] group-hover:shadow-[-2px_-2px_4px_0px_rgba(255,245,0,0.75)] rounded-3xl transition-shadow">
<!-- bottom -->
<div class="shadow-[2px_2px_4px_0px_rgba(112,0,255,0.25)] group-hover:shadow-[2px_2px_4px_0px_rgba(112,0,255,0.35)] rounded-3xl transition-shadow">
<div class="flex flex-col items-stretch w-full h-full">
    <a href={href} class="text-center px-5 py-3 rounded-3xl text-sm text-slate-600 group-hover:text-slate-900 group-hover:font-medium transition-all text-center">
        <slot/>
    </a>
</div>
</div></div></div></div>