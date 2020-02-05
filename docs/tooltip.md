<h6 class="text-muted text-uppercase">Components</h6>
<h1 class="h3 font-secondary">Tooltip</h1>
<hr class="border-bottom my-5">

<div class="box">
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="left" title="Tooltip on left" data-container="body" data-animation="true">On left</button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="top" title="Tooltip on top" data-container="body" data-animation="true">On top</button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="bottom" title="Tooltip on bottom" data-container="body" data-animation="true">On bottom</button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="right" title="Tooltip on right" data-container="body" data-animation="true">On right</button>
</div>

    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="left" title="Tooltip on left" data-container="body" data-animation="true">On left</button>

    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="top" title="Tooltip on top" data-container="body" data-animation="true">On top</button>

    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="bottom" title="Tooltip on bottom" data-container="body" data-animation="true">On bottom</button>

    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="right" title="Tooltip on right" data-container="body" data-animation="true">On right</button>

!> In order to use tooltips you have to initialize them.

    $(document).ready(function(){
        $(function () {
            $('[data-toggle="tooltip"]').tooltip()
        })
    });