# phpversion

Using phpinfo() to Discover the PHP Version and Modules Installed on your Server

    Create a file with one line in it:

    <?php phpinfo(); ?>

    Save the file as test.php
    Upload to your server
    Navigate to the page using your web browser

If PHP is installed on your server that single line of code will print out a heap of detailed information about the version and configuration of PHP you have available. If it is not installed the page will be returned blank.

Further reading: About phpinfo() on PHP.net.


<?php

// Show all information, defaults to INFO_ALL
phpinfo();

// Show just the module information.
// phpinfo(8) yields identical results.
phpinfo(INFO_MODULES);

?>
