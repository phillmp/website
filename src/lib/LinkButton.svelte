<script>
    export let href="void"
</script>
<!-- left -->
<div class="shadow-[inset_2px_0px_4px_0px_rgba(255,0,0,0.25)] hover:shadow-[inset_2px_0px_4px_0px_rgba(255,0,0,0.25)] rounded-xl transition-shadow bg-zinc-50 active:bg-zinc-100">
<!-- right -->
<div class="shadow-[inset_-2px_0px_4px_0px_rgba(15,171,238,0.25)] hover:shadow-[inset_-2px_0px_4px_0px_rgba(15,171,238,0.25)] rounded-xl transition-shadow">
<!-- top -->
<div class="shadow-[-2px_-2px_4px_0px_rgba(255,245,0,0.5)] hover:shadow-[-2px_-2px_4px_0px_rgba(255,245,0,0.75)] rounded-xl transition-shadow">
<!-- bottom -->
<div class="shadow-[2px_2px_4px_0px_rgba(112,0,255,0.25)] hover:shadow-[2px_2px_4px_0px_rgba(112,0,255,0.35)] rounded-xl transition-shadow">
<div class="flex">
    <a href={href} class="px-5 py-3 rounded-xl text-slate-600 hover:text-slate-900 transition-all">
        <slot/>
    </a>
</div>
</div></div></div></div>