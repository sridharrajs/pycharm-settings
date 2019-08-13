# pycharm-settings

A repo for my [PyCharm studio](https://www.jetbrains.com/pycharm/) settings 

### Command-line launcher

At times, you might want to launch pycharm on the current folder. To do so, configure commandline launcher.

> Tools -> Create Command-line Launcher

and add an `alias` in `.bashrc`

**.bashrc**

    # pc = pycharm
    alias pc='/usr/local/bin/charm'

From now on, you can open any project directory by `pc .` in it.


## Shortcuts

**dfg** stands for `div-form-group`


    <div class="form-group row">
      <label for="$1$" class="col-md-4 control-label">$2$</label>
      <div class="col-md-8">
        <input name="$1$" type="text" class="form-control" id="$1$">
      </div>
    </div>

