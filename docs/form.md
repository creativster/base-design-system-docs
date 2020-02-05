<h6 class="text-muted text-uppercase">Components</h6>
<h1 class="h3 font-secondary">Form</h1>
<hr class="border-bottom my-5">

<div class="box">
    <form>
        <div class="row">
            <div class="col-md-6">
            <div class="form-group">
                <input type="email" class="form-control" placeholder="name@example.com">
            </div>
            </div>
            <div class="col-md-6">
            <div class="form-group">
                <input type="text" placeholder="Disabled" class="form-control" disabled />
            </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
            <div class="form-group">
                <div class="input-group">
                <div class="input-group-prepend">
                    <span class="input-group-text"><i class="icon icon-user"></i></span>
                </div>
                <input class="form-control" placeholder="Username" type="text">
                </div>
            </div>
            </div>
            <div class="col-md-6">
            <div class="form-group">
                <div class="input-group">
                <input class="form-control" placeholder="Search" type="text">
                <div class="input-group-append">
                    <span class="input-group-text"><i class="icon icon-search"></i></span>
                </div>
                </div>
            </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
            <div class="form-group">
                <input type="text" placeholder="Success" class="form-control is-valid" />
            </div>
            </div>
            <div class="col-md-6">
            <div class="form-group">
                <input type="email" placeholder="Error Input" class="form-control is-invalid" />
            </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
            <div class="form-group">
                <input type="text" placeholder="Warning" class="form-control is-warning" />
            </div>
            </div>
            <div class="col-md-6">
            <div class="form-group">
                <input type="email" placeholder="Info Input" class="form-control is-info" />
            </div>
            </div>
        </div>
    </form>
</div>


    <div class="form-group">
        <input type="email" class="form-control" placeholder="name@example.com">
    </div>

    <div class="form-group">
        <input type="text" class="form-control" placeholder="Disabled" disabled />
    </div>

    <div class="form-group">
        <div class="input-group">
            <div class="input-group-prepend">
                <span class="input-group-text"><i class="icon icon-user"></i></span>
            </div>
            <input class="form-control" placeholder="Username" type="text">
        </div>
    </div>

    <div class="form-group">
        <div class="input-group">
            <input class="form-control" placeholder="Search" type="text">
            <div class="input-group-append">
                <span class="input-group-text"><i class="icon icon-search"></i></span>
            </div>
        </div>
    </div>

    <div class="form-group">
        <input type="text" class="form-control is-valid" placeholder="Success"  />
    </div>

    <div class="form-group">
        <input type="email" class="form-control is-invalid" placeholder="Error Input" />
    </div>

    <div class="form-group">
        <input type="text" class="form-control is-warning" placeholder="Warning" />
    </div>

    <div class="form-group">
        <input type="email" class="form-control is-info" placeholder="Info Input" />
    </div>
?> Add `is-valid`, `is-invalid`, `is-warning`, `is-info` to the `.form-control` class to change the status of the field.

<hr class="border-bottom">

<h2 class="h4">Alternative style</h2>

<div class="box">
    <form>
        <div class="row">
            <div class="col-md-6">
            <div class="form-group alternative">
                <input type="email" class="form-control" placeholder="user@example.com">
            </div>
            </div>
            <div class="col-md-6">
            <div class="form-group alternative">
                <input type="text" placeholder="Disabled" class="form-control" disabled />
            </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
            <div class="form-group alternative">
                <div class="input-group mb-4">
                <div class="input-group-prepend">
                    <span class="input-group-text"><i class="icon icon-user"></i></span>
                </div>
                <input class="form-control" placeholder="Username" type="text">
                </div>
            </div>
            </div>
            <div class="col-md-6">
            <div class="form-group alternative">
                <div class="input-group mb-4">
                <input class="form-control" placeholder="Search" type="text">
                <div class="input-group-append">
                    <span class="input-group-text"><i class="icon icon-search"></i></span>
                </div>
                </div>
            </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
            <div class="form-group alternative">
                <input type="text" placeholder="Success" class="form-control is-valid" />
            </div>
            </div>
            <div class="col-md-6">
            <div class="form-group alternative">
                <input type="email" placeholder="Error Input" class="form-control is-invalid" />
            </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
            <div class="form-group alternative">
                <input type="text" placeholder="Warning" class="form-control is-warning" />
            </div>
            </div>
            <div class="col-md-6">
            <div class="form-group alternative">
                <input type="email" placeholder="Info Input" class="form-control is-info" />
            </div>
            </div>
        </div>
    </form>
</div>

?> Add class `alternative` to `form-group` class in order to change the style.

    <div class="form-group alternative">
        <input type="text" class="form-control" placeholder="user@example.com">
    </div>

<hr class="border-bottom">

<h2 class="h4">Select field</h2>

<form class="box">
    <div class="row">
        <div class="col">
            <div class="form-group">
                <select id="selectId" class="form-control">
                    <option hidden>Select</option>
                    <option value="1">Default</option>
                    <option value="2">System</option>
                    <option value="3">Select</option>
                    <option value="4">List</option>
                </select>
            </div>
        </div>
        <div class="col">
            <div class="form-group alternative">
                <select id="selectId" class="form-control">
                    <option hidden>Select</option>
                    <option value="1">Option 1</option>
                    <option value="2">Option 2</option>
                    <option value="3">Option 3</option>
                    <option value="4">Option 4</option>
                </select>
            </div>
        </div>
    </div>
</form>

    <div class="form-group">
        <select id="selectId" class="form-control">
            <option hidden>Select</option>
            <option value="1">Option 1</option>
            <option value="2">Option 2</option>
            <option value="3">Option 3</option>
            <option value="4">Option 4</option>
        </select>
    </div>

    <div class="form-group alternative">
        <select id="selectId" class="form-control">
            <option hidden>Select</option>
            <option value="1">Option 1</option>
            <option value="2">Option 2</option>
            <option value="3">Option 3</option>
            <option value="4">Option 4</option>
        </select>
    </div>
<hr class="border-bottom">

<h2 class="h4">Textarea</h2>

<div class="box">
    <div class="row">
        <div class="col-6">
            <div class="form-group">
                <textarea class="form-control" rows="3" placeholder="Textarea ..."></textarea>
            </div>
        </div>
        <div class="col-6">
            <div class="form-group alternative">
                <textarea class="form-control" rows="3" placeholder="Textarea ..."></textarea>
            </div>
        </div>
    </div>
</div>

    <div class="form-group">
        <textarea class="form-control" rows="3" placeholder="Textarea ..."></textarea>
    </div>

    <div class="form-group alternative">
        <textarea class="form-control" rows="3" placeholder="Textarea ..."></textarea>
    </div>
<hr class="border-bottom">

<h2 class="h4">Checkbox</h2>

<div class="box">
    <input type="checkbox" class="checkbox">
    Check me!
    <hr>
    <input type="checkbox" class="checkbox" checked>
    I'm already checked.
    <hr>
    <input type="checkbox" class="checkbox" disabled>
    I'm disabled.
    <hr>
    <input type="checkbox" class="checkbox" checked disabled>
    I'm checked and disabled.
</div>

    <input type="checkbox" class="checkbox">
    Check me!

    <input type="checkbox" class="checkbox" checked>
    I'm already checked.

    <input type="checkbox" class="checkbox" disabled>
    I'm disabled.

    <input type="checkbox" class="checkbox" checked disabled>
    I'm checked and disabled.

<hr class="border-bottom">

<h2 class="h4">Toggle</h2>

<div class="box">
    <input type="checkbox" class="toggle">
    Toggle me!
    <hr>
    <input type="checkbox" class="toggle" checked>
    I'm already toggled.
    <hr>
    <input type="checkbox" class="toggle" disabled>
    I'm disabled.
    <hr>
    <input type="checkbox" class="toggle" checked disabled>
    I'm toggled and disabled.
</div>

    <input type="checkbox" class="toggle">
    Toggle me!
    
    <input type="checkbox" class="toggle" checked>
    I'm already toggled.
    
    <input type="checkbox" class="toggle" disabled>
    I'm disabled.
    
    <input type="checkbox" class="toggle" checked disabled>
    I'm toggled and disabled.

<hr class="border-bottom">

<h2 class="h4">Radio</h2>

<div class="box">
    <input type="radio" class="radio" name="radio">
    Switch
    <input type="radio" class="radio" name="radio">
    between us
</div>

    <input type="radio" class="radio" name="radioExample">
    Switch
    <input type="radio" class="radio" name="radioExample">
    between us