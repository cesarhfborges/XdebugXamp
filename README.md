# XdebugXamp
Habilitar XDebug no Xamp - PhpStorm e outras ide's


Abrir o Arquivo Php.ini
Colar no Final do seu arquivo salvar e pronto

Caso tenha alterado o local padrão do xdebug é so alterar os prefixos das pastas para a sua
Não precisa baxiar nada

[XDebug]
zend_extension = "c:\xampp\php\ext\php_xdebug.dll"
;zend_extension = "c:\xampp\php\ext\php_xdebug-2.7.2-7.3-vc15-x86_64.dll"
xdebug.remote_autostart = 1
xdebug.profiler_append = 0
xdebug.profiler_enable = 0
xdebug.profiler_enable_trigger = 0
xdebug.profiler_output_dir = "c:\xampp\tmp"
;xdebug.profiler_output_name = "cachegrind.out.%t-%s"
xdebug.remote_enable = 1
xdebug.remote_handler = "dbgp"
xdebug.remote_host = "127.0.0.1"
xdebug.remote_log = "c:\xampp\tmp\xdebug.txt"
xdebug.remote_port = 9000
xdebug.trace_output_dir = "c:\xampp\tmp"
;36000 = 10h
xdebug.remote_cookie_expire_time = 36000
