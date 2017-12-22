haxelib install hxcpp
haxelib install hxjava

haxe -main HelloWorld.hx -cpp cppout
haxe -main HelloWorld.hx -java javaout

haxe -main HelloWorld --interp
