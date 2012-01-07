# Nested Asset Example

If we rename the manifest files in each of the asset sub-directories to **application.css**, we don't 
have to explicitly state them in `config.assets_precompile`

Have a peek in the asset dirs to see what I mean - then run `rake assets:precompile` and have a look at the generated files in public/assets

This is much more scalable solution

Bo'