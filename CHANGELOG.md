# 2.0.0 (2018-05-08)

* Migrate to Angular and rxjs version 6

# 1.0.9 (2018-05-04)

* Added `undo` and `redo` events to ngModel onChangeCallback.

# 1.0.8 (2018-04-26)

* Added null check before removing editor to check that tinymce is actually available.

# 1.0.7 (2018-04-06)

* Fixed bug with onInit not firing and removed onPreInit shorthand.

# 1.0.6 (2018-04-06)

* Changed so tinymce.init is run outside of angular with ngzone.

# 1.0.5 (2018-02-15)

* Fixed bug where is wasn't possible to set inline in the init object, only on the shorthand.

# 1.0.4 (2018-02-14)

* Fixed bug where the component threw errors because it tried to setContent on an editor that had not been initialized fully.

# 1.0.3 (2018-02-13)

* Fixed bug where the component threw errors on change when not used together with the forms module.
