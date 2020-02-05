<h6 class="text-muted text-uppercase">Components</h6>
<h1 class="h3 font-secondary">Popover</h1>
<hr class="border-bottom my-5">

<div class="box">
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="top" data-content="Lorem ipsum dolor sit amet. consectetur adipiscing elit.">
    Popover on top
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="right" data-content="Lorem ipsum dolor sit amet. consectetur adipiscing elit.">
    Popover on right
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="bottom" data-content="Lorem ipsum dolor sit amet. consectetur adipiscing elit.">
    Popover on bottom
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="left" data-content="Lorem ipsum dolor sit amet. consectetur adipiscing elit.">
    Popover on left
    </button>
</div>

    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="top" data-content="Lorem ipsum dolor sit amet. consectetur adipiscing elit.">
    Popover on top
    </button>

    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="right" data-content="Lorem ipsum dolor sit amet. consectetur adipiscing elit.">
    Popover on right
    </button>

    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="bottom" data-content="Lorem ipsum dolor sit amet. consectetur adipiscing elit.">
    Popover on bottom
    </button>

    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="left" data-content="Lorem ipsum dolor sit amet. consectetur adipiscing elit.">
    Popover on left
    </button>

!> In order to use popovers you have to initialize them.

    $( document ).ready(function() {
        $(function () {
            $('[data-toggle="popover"]').popover()
        })
    });
