<h6 class="text-muted text-uppercase">Foundation</h6>
<h1 class="h3 font-secondary">Colors</h1>
<hr class="border-bottom my-5">

<p class="font-primary">
The <strong class="font-weight-600">Color palette</strong> is composed of pale colors. These colors offer a modern, fresh and warm vibe. Colors should be used in meaningful ways in order to create patterns and visual cues.
</p>

<hr class="border-bottom my-5">

<h2 class="h4">Color palette</h2>

<div class="row my-4">
    <div class="col">
        <div class="card py-5 bg-default border-0">
        </div>
        <h6 class="text-default text-center mt-2">Default - #FF6362</h6>
    </div>
    <div class="col">
        <div class="card py-5 bg-primary border-0">
        </div>
        <h6 class="text-primary text-center mt-2">Primary - #202677</h6>
    </div>
    <div class="col">
        <div class="card py-5 bg-secondary border-0">
        </div>
        <h6 class="text-secondary text-center mt-2">Secondary - #C8C3CD</h6>
    </div>
</div>
<div class="row my-4">
    <div class="col">
        <div class="card py-5 bg-info border-0">
        </div>
        <h6 class="text-info text-center mt-2">Info - #11CDEF</h6>
    </div>
    <div class="col">
        <div class="card py-5 bg-success border-0">
        </div>
        <h6 class="text-success text-center mt-2">Success - #2DCE89</h6>
    </div>
    <div class="col">
        <div class="card py-5 bg-warning border-0">
        </div>
        <h6 class="text-warning text-center mt-2">Warning - #FFBA41</h6>
    </div>
        <div class="col">
        <div class="card py-5 bg-danger border-0">
        </div>
        <h6 class="text-danger text-center mt-2">Danger - #FF4242</h6>
    </div>
</div>

<hr class="border-bottom my-5">


<div><strong class="text-primary">🎨 Customize 🎨</strong>: You can also customize your theme primary colors by changing the variables inside <code>scss/__variables.scss</code> and compiling the <code>scss/theme.scss</code> file with <code><a class="underline" href="https://sass-lang.com/install" target="_blank">https://sass-lang.com/install</a></code> using the command: <code>sass scss/theme.scss base.css</code>, this will give you 2 new files, <code>base.css</code> and <code>base.css.map</code> that you will have to include just like in the 2nd step above.</div><br>

<hr class="border-bottom my-5">

<h2 class="h4">Greyscale</h2>

<p class="font-primary">
Greyscale colors offer a warmth feel around components in contrast on white backgrounds. These Greyscale color variables are available as SCSS variables in the <code>scss/_variables.scss</code> file and as CSS variables with the code: <code>var(--color-[greyscale])</code>
</p>

<table class="table">
<thead>
    <tr><th>SCSS / CSS variable</th>
    <th>HEX</th></tr>
</thead>
<tbody>
    <tr><td><div class="avatar rounded" style="background-color: #f6f9fc;"></div> <code>$gray-100 / gray-100</code></td><td><code>#f6f9fc</code></td></tr>
    <tr><td><div class="avatar rounded" style="background-color: #e9ecef;"></div> <code>$gray-200 / gray-200</code></td><td><code>#e9ecef</code></td></tr>
    <tr><td><div class="avatar rounded" style="background-color: #dee2e6;"></div> <code>$gray-300 / gray-300</code></td><td><code>#dee2e6</code></td></tr>
    <tr><td><div class="avatar rounded" style="background-color: #ced4da;"></div> <code>$gray-400 / gray-400</code></td><td><code>#ced4da</code></td></tr>
    <tr><td><div class="avatar rounded" style="background-color: #c0c8cf;"></div> <code>$gray-500 / gray-500</code></td><td><code>#c0c8cf</code></td></tr>
    <tr><td><div class="avatar rounded" style="background-color: #9fadbd;"></div> <code>$gray-600 / gray-600</code></td><td><code>#9fadbd</code></td></tr>
    <tr><td><div class="avatar rounded" style="background-color: #525f7f;"></div> <code>$gray-700 / gray-700</code></td><td><code>#525f7f</code></td></tr>
    <tr><td><div class="avatar rounded" style="background-color: #32325d;"></div> <code>$gray-800 / gray-800</code></td><td><code>#32325d</code></td></tr>
    <tr><td><div class="avatar rounded" style="background-color: #212529;"></div> <code>$gray-900 / gray-900</code></td><td><code>#212529</code></td></tr>
</tbody>
</table>

<hr class="border-bottom my-5">

<h2 class="h4">Text & background color modifiers</h2>

<p class="font-primary">
Components and typography have color variations thanks to these class modifiers <code>.bg-[color]</code>, <code>.bg-[color]-gradient</code> , <code>.text-[color]</code>.
</p>
<hr>

<table class="table is-bordered">
<thead>
    <tr><th>Target</th>
    <th>Class pattern</th></tr>
</thead>
<tbody>
    <tr><td>Background</td><td><code>.bg-[color]</code> , <code>.bg-[color]-gradient</code></td></tr>
    <tr><td>Text</td><td><code>.text-[color]</code></td></tr>
</tbody>
</table>

<hr class="border-bottom my-5">

<h2 class="h4">CSS variables</h2>

<p class="font-primary">
All colors are available as CSS variables through the code: <code>var(--color-[color])</code>.
</p>

    .text-selector{
        color: var(--color-primary);
    }

    .background-selector{
        background-color: var(--color-secondary);
    }
