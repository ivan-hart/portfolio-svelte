<script>
    import Project from "./Project.svelte";
</script>

<main>
<section id="projects" class="grid">
    <div class="div1 center">
        <h3>Projects</h3>
    </div>
    <div class="div2">
        <Project text="project" />
    </div>
    <div class="div3">
        <Project text="project" />
    </div>
    <div class="div4">
        <Project text="project" />
    </div>
    <div class="div5">
        <Project text="project" />
    </div>
</section>
<section id="projects" class="grid">
    <div class="div1 center">
        <h3>Projects</h3>
    </div>
    <div class="div2">
        <Project text="project" />
    </div>
    <div class="div3">
        <Project text="project" />
    </div>
    <div class="div4">
        <Project text="project" />
    </div>
    <div class="div5">
        <Project text="project" />
    </div>
</section>
<section id="projects" class="grid">
    <div class="div1 center">
        <h3>Projects</h3>
    </div>
    <div class="div2">
        <Project text="project" />
    </div>
    <div class="div3">
        <Project text="project" />
    </div>
    <div class="div4">
        <Project text="project" />
    </div>
    <div class="div5">
        <Project text="project" />
    </div>
</section>
<section id="projects" class="grid">
    <div class="div1 center">
        <h3>Projects</h3>
    </div>
    <div class="div2">
        <Project text="project" />
    </div>
    <div class="div3">
        <Project text="project" />
    </div>
    <div class="div4">
        <Project text="project" />
    </div>
    <div class="div5">
        <Project text="project" />
    </div>
</section>
<section id="projects" class="grid">
    <div class="div1 center">
        <h3>Projects</h3>
    </div>
    <div class="div2">
        <Project text="project" />
    </div>
    <div class="div3">
        <Project text="project" />
    </div>
    <div class="div4">
        <Project text="project" />
    </div>
    <div class="div5">
        <Project text="project" />
    </div>
</section>
<section id="projects" class="grid">
    <div class="div1 center">
        <h3>Projects</h3>
    </div>
    <div class="div2">
        <Project text="project" />
    </div>
    <div class="div3">
        <Project text="project" />
    </div>
    <div class="div4">
        <Project text="project" />
    </div>
    <div class="div5">
        <Project text="project" />
    </div>
</section>
</main>

<style>
main:nth-child(odd) {
    background-color: #aaaaaa;
}
.grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-column-gap: 25px;
    grid-row-gap: 25px;
}

.div1 { 
    grid-area: 1 / 1 / 3 / 2; 
}

.div2 { 
    grid-area: 1 / 2 / 2 / 3; 
}

.div3 { 
    grid-area: 1 / 3 / 2 / 4; 
}

.div4 { 
    grid-area: 2 / 2 / 3 / 3; 
}

.div5 { 
    grid-area: 2 / 3 / 3 / 4; 
}

section {
    padding-block: 30px;
}
</style>