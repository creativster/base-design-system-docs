<h6 class="text-muted text-uppercase">Components</h6>
<h1 class="h3 font-secondary">Toast</h1>
<hr class="border-bottom my-5">

<div class="box">
    <div class="toast fade show" role="alert" aria-live="assertive" data-autohide="false" aria-atomic="true">
    <div class="toast-header">
        <span class="avatar avatar-sm mr-auto"></span>
        <small>11 mins ago</small>
        <button type="button" class="ml-2 mb-1 close" data-dismiss="toast" aria-label="Close">
        <span aria-hidden="true">&times;</span>
        </button>
    </div>
    <div class="toast-body">
        Hello, world! This is a toast message.
    </div>
    </div>
</div>

    <div class="toast fade show" data-autohide="false" role="alert" aria-live="assertive" aria-atomic="true">
        <div class="toast-header">
            <span class="avatar avatar-sm mr-auto"></span>
            <small>11 mins ago</small>
            <button type="button" class="ml-2 mb-1 close" data-dismiss="toast" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
        </div>
        <div class="toast-body">
            Hello, world! This is a toast message.
        </div>
    </div>

!> In order to use toasts you have to initialize them.

    $(document).ready(function(){
        $('.toast').toast('show');
    });