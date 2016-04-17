##Presets
 Presets are commonly used sets of babel plugins.

 ##Plugins

*  transform-runtime
   * All the small helper functions that babel uses
   are normally added to every file that requires it.
   This plugin makes it so these helper functions will
   all reference the module babel-runtime to reduce
   duplication across compiled output.

*


##env
Set specific options that are enabled
based on the value of the environment var BABEL_ENV.
If BABEL_ENV undefined, NODE_ENV. If that is also undefined,
the default is 'development'

