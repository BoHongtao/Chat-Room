# chat-room
1，打开php.ini，打开extension=php_gd2.dll和extension=php_sockets.dll扩展；\n
2，确保phpinfo中socket模块是否为enable;\n
3，如果你使用的unix或者linux，请使用get_current_user()，windows请使用posix_getpid()，在构造函数里面大约30行的地方
