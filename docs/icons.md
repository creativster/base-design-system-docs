<h6 class="text-muted text-uppercase">Foundation</h6>
<h1 class="h3 font-secondary">Iconography</h1>
<hr class="border-bottom my-5">

<p class="font-primary">
<span class="font-weight-600">Base Design System</span> uses <span class="font-weight-600">Feather Icons <i class="icon icon-feather" style="font-size: 1rem;"></i></span>. The icon set is composed of 280 icons which are looking great in combination with modern components. Make sure you check all of them at <span class="font-weight-600 underline"><a href="https://feathericons.com/?ref=basedesignsystem" target="_blank" rel="nofollow">Feather Icons</a> <i class="icon icon-feather" style="font-size: 1rem;"></i></span>.
</p>

<hr class="border-bottom my-5">
<h2 class="h4">Implementation</h2>

<p class="font-primary">
In order to use the icon pack you will need to include the <code>iconography.css</code> CSS file in the <code>head</code> section of your page before the design system main css (<code>base.css</code>) file:
</p>

    <head>
        <link rel="stylesheet" href="iconography.css">
        <link rel="stylesheet" href="base.css">
    </head>

!> Make sure to also include the ```icon-fonts``` folder in the same directory as the ```iconography.css``` or change the ```url()``` path inside ```iconography.css``` to point to the ```icon-fonts``` folder.
<hr class="border-bottom my-5"><br>

<h2 class="h4">How to use</h2>

<p class="font-primary">
We recommend using a consistent HTML element, like <code>i</code>. In order to use the icons, the element should use class <code>icon</code>.
</p>

<i class="icon icon-feather"></i>

    <i class="icon icon-[name]"></i>
?> The icon color can be changed by adding a color modifier class to it ```icon-color-[color]```

<hr class="border-bottom">

<h2 class="h4">Icon styles</h2>

<i class="icon icon-feather icon-color-primary fill round"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-color-default fill"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-color-info outline"></i>

    <i class="icon icon-feather icon-color-primary fill round"></i>

    <i class="icon icon-feather icon-color-default fill"></i>

    <i class="icon icon-feather icon-color-info outline"></i>
<hr class="border-bottom">

<h2 class="h4">Icon sizes</h2>

<i class="icon icon-feather icon-sm"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-md"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-lg"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-xl"></i>
&nbsp;
&nbsp;

    <i class="icon icon-feather icon-sm"></i> - 0.8rem;

    <i class="icon icon-feather icon-md"></i> - 1.5rem;

    <i class="icon icon-feather icon-lg"></i> - 2rem;

    <i class="icon icon-feather icon-xl"></i> - 2.5rem;
?> You can also set the size in pixels

<i class="icon icon-feather icon-color-primary icon-12 fill"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-color-primary icon-16 fill"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-color-primary icon-24 fill"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-color-primary icon-32 fill"></i>
&nbsp;
&nbsp;
<i class="icon icon-feather icon-color-primary icon-48 fill"></i>
&nbsp;
&nbsp;

    <i class="icon icon-feather icon-color-primary icon-12 fill"></i> - 12px

    <i class="icon icon-feather icon-color-primary icon-16 fill"></i> - 16px

    <i class="icon icon-feather icon-color-primary icon-24 fill"></i> - 24px

    <i class="icon icon-feather icon-color-primary icon-32 fill"></i> - 32px

    <i class="icon icon-feather icon-color-primary icon-48 fill"></i> - 48px