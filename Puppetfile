forge 'http://forge.puppetlabs.com'

# Modules from the Puppet Forge

# letsencrypt/dehydrated
#mod 'bzed/letsencrypt', '0.1.16'
# JC - 2017/03/16
# using github fork until https://github.com/bzed/bzed-letsencrypt/pull/27 is
# merged which should allow setting the certs base_dir to something other than
# /etc/letsencrypt which will fix SELinux headaches.
mod 'letsencrypt',
  :git => 'https://github.com/siliconalchemy/bzed-letsencrypt.git',
  :ref => 'b29b64ce35390baa10a56c2c2a1c30a68e1e42c6'

# Camptocamp
mod 'camptocamp/augeas', '1.5.1'
mod 'camptocamp/dell', '0.5.1'
mod 'camptocamp/openldap', '1.15.0'
mod 'camptocamp/openssl', '1.8.2'
mod 'camptocamp/postfix', '1.4.0'
mod 'camptocamp/puppetserver', '2.1.0'
mod 'camptocamp/selinux', '0.3.1'

mod 'croddy/make', '0.0.5'
mod 'darin/zypprepo', '1.0.2'
mod 'dalen/puppetdbquery', '2.2.0'
mod 'datacentred/external_facts', '1.1.0'
mod 'dhoppe/screen', '1.1.1'
mod 'dprince/qpid', '1.0.3'
mod 'engage/uwsgi', '1.2.0'
mod 'garethr/erlang', '0.3.0'
mod 'gentoo/portage', '2.3.0'

# ghoneycutt
mod 'ghoneycutt/common', '1.6.0'
mod 'ghoneycutt/hosts', '2.4.0'
#mod 'ghoneycutt/nfs', :latest
# NOTE: last check (v1.11.2) still did not support EL7
# override forge module as it is broken for EL7
mod 'nfs',
  :git => 'https://github.com/ghoneycutt/puppet-module-nfs.git',
  :branch => 'el7'
mod 'ghoneycutt/nsswitch', '1.4.0'
# fork of ghoneycutt/pam (was originally forked by herlo but since he isn't here
# anymore tykeal pulled a fork so we could pin to an LF employee till we can get
# changes pushed into upstream
mod 'pam',
  :git => 'https://github.com/tykeal/puppet-module-pam.git',
  :ref => 'f604cd2a9c7e884acbc261c226420d862affe8cc'
mod 'ghoneycutt/rpcbind', '1.6.1'
mod 'ghoneycutt/types', '1.10.0'
mod 'ghoneycutt/vim', '2.11.0'

# herculesteam
mod 'herculesteam/augeasproviders_core', '2.1.3'
mod 'herculesteam/augeasproviders_shellvar', '2.2.1'

#mod 'hubspot/nexus', '1.7.1'
# upgrade to latest version (1.7.1) + patch that correctly supports nexus 3
# since an update with it hasn't been released yet. Targeted for 1.7.2
mod 'nexus',
  :git => 'https://github.com/hubspotdevops/puppet-nexus',
  :ref => '7dffd1378f11da7c96122f8175980f7536a3c87f'

# inkblot
mod 'inkblot/bind', '6.0.1'
mod 'inkblot/shorewall', '5.0.1'

mod 'jhoblitt/nsstools', '2.0.0'

#mod 'jlcox/gitolite', '1.2.3'
# PR#5 has been made to incorporate this work
mod 'gitolite',
  :git => 'https://github.com/tykeal/puppet-gitolite.git',
  :ref => 'd88d406f07313cc7de2624a604d056ca2172a12a'

# kemra102
mod 'kemra102/auditd', '2.0.1'
mod 'kemra102/ius', '1.1.0'

mod 'maestrodev/wget', '1.7.3'
mod 'mkrakowitzer/deploy', '0.0.3'
# point to a git version so we can do some debugging to create some patches
#mod 'mthibaut/users', '1.0.11'
mod 'users',
  :git => 'https://github.com/tykeal/puppet-users.git',
  :ref => '47559be0582fe95951507ae4ce1c17b4eb9de907'

# Openstack
mod 'openstack/cinder', '7.0.0'
mod 'openstack/glance', '7.0.0'
mod 'openstack/horizon', '7.0.0'
mod 'openstack/keystone', '7.0.0'
mod 'openstack/neutron', '7.0.0'
mod 'openstack/nova', '7.0.0'
mod 'openstack/openstacklib', '7.0.0'
mod 'openstack/openstack_extras', '7.0.0'
mod 'openstack/vswitch', '3.0.0'

mod 'pdxcat/nrpe', '2.1.1'

# Puppet community
mod 'puppet/archive',  '1.1.2'
mod 'puppet/confluence', '2.2.2'
mod 'puppet/jira', '3.1.0'
mod 'puppet/mcollective', '2.3.0'
mod 'puppet/mysql_java_connector', '2.2.0'
mod 'puppet/nginx', '0.5.0'
mod 'puppet/staging', '2.0.1'

# Puppetlabs
mod 'puppetlabs/apache', '1.10.0'
mod 'puppetlabs/apt', '2.2.2'
mod 'puppetlabs/concat', '2.2.0'
mod 'puppetlabs/firewall', '1.8.1'
mod 'puppetlabs/gcc', '0.3.0'
mod 'puppetlabs/git', '0.5.0'
mod 'puppetlabs/inifile', '1.6.0'
mod 'puppetlabs/java', '1.6.0'
mod 'puppetlabs/java_ks', '1.4.1'
mod 'puppetlabs/mysql', '3.9.0'
mod 'puppetlabs/ntp', '4.2.0'
mod 'puppetlabs/pe_gem', '0.2.0'
mod 'puppetlabs/puppetdb', '5.1.2'
mod 'puppetlabs/postgresql', '4.8.0'
mod 'puppetlabs/rabbitmq', '5.5.0'
mod 'puppetlabs/ruby', '0.5.0'
mod 'puppetlabs/stdlib', '4.13.1'
mod 'puppetlabs/tagmail', '2.1.1'
mod 'puppetlabs/tomcat', '1.5.0'
mod 'puppetlabs/vcsrepo', '1.4.0'
mod 'puppetlabs/xinetd', '2.0.0'

mod 'razorsedge/network', '3.8.0'
mod 'richardc/datacat', '0.6.2'
mod 'rmueller/cron', '0.1.3'
mod 'rtyler/jenkins', '1.7.0'

# stm
mod 'stm/haveged', '0.2.0'

# saz
mod 'saz/dnsmasq', '1.2.0'
mod 'saz/memcached', '2.8.1'
mod 'saz/resolv_conf', '3.0.5'
mod 'saz/rsyslog', '3.5.1'
mod 'saz/ssh', '2.9.1'
mod 'saz/sudo', '3.1.0'
mod 'saz/timezone', '3.3.0'

#mod 'srf/rkhunter', '0.1.4'
# temporary override
mod 'rkhunter',
  :git => 'https://github.com/mmz-srf/puppet-rkhunter.git',
  :ref => '803ebabed06c4052ec03afdc876604abb2ac136e'

mod 'stahnma/epel', '1.2.2'
# need https://github.com/stankevich/puppet-python/pull/359
#mod 'stankevich/python', '1.18.2'
mod 'python',
  :git => 'https://github.com/stankevich/puppet-python.git',
  :ref => '4af8ebbad751320330d86c42fc65cfc1e4a2168c'

# thias
mod 'thias/libvirt', '1.0.0'
mod 'thias/sysctl', '1.0.6'

# tykeal
mod 'tykeal/clm', '1.0.0'
mod 'tykeal/gerrit', '1.1.1'
mod 'tykeal/ini_config', '1.1.0'
mod 'tykeal/jjb', '1.0.2'
mod 'tykeal/nagios', '1.0.0'
#mod 'tykeal/nodepool', ''
mod 'nodepool',
  :git => 'https://github.com/tykeal/puppet-nodepool.git'
mod 'tykeal/sslmgmt', '1.0.1'
#mod 'tykeal/zuul', ''
mod 'zuul',
  :git => 'https://github.com/tykeal/puppet-zuul.git'
mod 'zack/r10k', '3.2.0'

# fork of herlo/totpcgi that has never hit the forge. Since herlo isn't here
# anymore tykeal pulled a fork so we could pin to an LF employee till we can
# re-evaluate / get released to the forge
mod 'totpcgi',
  :git => 'https://github.com/mricon/puppet-totpcgi.git',
  :ref => '4c764a6f96e0d3d5d73e5861e214d2fb6d22db45'


# custom modules

# correct User for gerrit.linuxfoundation.org
mod 'profile',
  :git => 'https://github.com/tykeal/puppetserver-mod-profile.git'

mod 'role',
  :git => 'https://github.com/tykeal/puppetserver-mod-role.git'

mod 'local_fw',
  :git => 'https://github.com/tykeal/puppetserver-mod-local_fw.git'

# vim: sw=2 sts=2 ts=2 et :
