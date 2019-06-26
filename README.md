# php-memcached for windows
 * php-memcached dependency libmemcached

        copy libmemcached.dll to Windows 
        
  
        
 * install php-memcached
 
    copy php-memcached.dll to you php extension directory
    
    **notice:Note the version of PHP and thread safety whether or not**
    
    * memcached_support:
    
    |name|is_support|
    ----|----------
    |SASL support|no|
    |Session support|yes|
    |igbinary support|no|
    |json support|yes|
    |msgpack support|no|
	
	
Tips:
ucrtbased.dll missing copy ucrtbased to system32 or SysWOW64
    
    
     
