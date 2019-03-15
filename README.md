# php-memcached for windows
 * php-memcached dependency libmemcached

     1. x64 system
        
        copy libmemcached/libmemcached_x64.dll to Windows 
        
        remame libmemcached_x64.dll to libmemcached.dll
     2. x86 system
  
        copy libmemcached/libmemcached_x86.dll to Windows 
        
        remame libmemcached_x86.dll to libmemcached.dll
        
 * install php-memcached
 
    copy php-memcached.dll to you php extension directory
    
    **notice:Note the version of PHP and thread safety whether or not,enable igbinary extension**
    
    * memcached_support:
    
    |name|is_support|
    ----|----------
    |SASL support|no|
    |Session support|yes|
    |igbinary support|yes|
    |json support|yes|
    |msgpack support|no|
    
    
   build platform:win7 enterprise
     
