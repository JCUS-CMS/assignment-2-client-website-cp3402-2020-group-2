# CP3402-2020 CMS: Assignmnet 2 - GROUP 2
## Group Members ##
<b>1. Kexin Tao</b><br>
<b>2. Le Chang</b><br>
<b>3. Ming Zhou</b><br>
<b>4. Mingcan Weng</b><br>
<b>5. Siyuan Yang</b>
***
## Brief Description ##
This is a group project for developing and deploying a website called <b>Doctors Connect</b> using WordPress, and the website is designed using our own custom theme created based on a 'Starter Theme' - Underscore.<br>
Doctors Connect Foundation Malaysia’s sole aim is in creating access for quality healthcare to remote inaccessible and poor socio-economic areas to provide quality medical screening and care for the needy and unfortunate irrespective of race, religion or nationality. And our job is to design a nice website for it to attract more volunteers.
***
## Prerequisites ##
### Virtual Local Environment Setup ###
###  Scoatch Box -> Vagrant ###
Why Scoatch Box?<br>
Scotch Box is a pre-configured Vagrant Box with a full array of features to get us up and running with Vagrant in no time.<br>
Download the files to the computer from https://github.com/scotch-io/scotch-box.<br>
Or you can open cmd and simply type as following:
<pre><code>git clone https://github.com/scotch-io/scotch-box CP3402-Project
cd CP3402-Project
vagrant up。
</code></pre>
Then you will see the following in your console once the local environment finishes setting up:

<pre><code>==> vagrant: A new version of Vagrant is available: 2.2.10 (installed version: 2.2.9)!
==> vagrant: To upgrade visit: https://www.vagrantup.com/downloads.html

Bringing machine 'default' up with 'virtualbox' provider...
==> default: Checking if box 'scotch/box' version '3.5' is up to date...
==> default: Clearing any previously set forwarded ports...
==> default: Clearing any previously set network interfaces...
==> default: Preparing network interfaces based on configuration...
    default: Adapter 1: nat
    default: Adapter 2: hostonly
==> default: Forwarding ports...
    default: 22 (guest) => 2222 (host) (adapter 1)
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2222
    default: SSH username: vagrant
    default: SSH auth method: private key
==> default: Machine booted and ready!
==> default: Checking for guest additions in VM...
    default: The guest additions on this VM do not match the installed version of
    default: VirtualBox! In most cases this is fine, but in rare cases it can
    default: prevent things such as shared folders from working properly. If you see
    default: shared folder errors, please make sure the guest additions within the
    default: virtual machine match the version of VirtualBox you have installed on
    default: your host and reload your VM.
    default:
    default: Guest Additions Version: 5.1.21
    default: VirtualBox Version: 6.1
==> default: Setting hostname...
==> default: Configuring and enabling network interfaces...
==> default: Mounting shared folders...
    default: /var/www => C:/Users/95183/Desktop/wordpress
==> default: Machine already provisioned. Run `vagrant provision` or use the `--provision`
==> default: flag to force provisioning. Provisioners marked to run always will still run.</code></pre>
***
## Deployment ##
<b>ScoatchBox/Vagrant</b> (Local)<br>
<b>Siteground</b> (Staging)<br>
<b>Siteground</b> (Production)
