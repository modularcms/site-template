# modularcms site template
This is the entrypoint for your website. If you're not familiar with modularcms check this out first: https://modularcms.io

## How to install?
1. Get access to the webhost that is associated with your domain via SSH / FTP / SFTP
1. Navigate to the folder that is corresponding to your domain and your base url (typically the "htdocs" folder)
1. Upload all extracted files of this .zip to the folder (alternatively if your using ssh you can execute `git clone https://github.com/modularcms/site-template.git .`)
1. Make sure that the .htaccess file is uploaded and your server has the feature ModRewrite enabled
1. Have fun with your new component based website

If your using plesk the installation process is even easier. Just enable the usage of git on the creation of your domain and enter the url of this repository (`https://github.com/modularcms/site-template.git`).