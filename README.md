
1. In php.ini

post_max_size = 8M
upload_max_filesize = 2M
max_execution_time = 30
max_input_time = 60
memory_limit = 8M

2. In my.ini (MySQL File)

max_allowed_packet = 500M

3. Add this line to config.inc.php in phpMyAdmin

$cfg['ExecTimeLimit'] = 0;
