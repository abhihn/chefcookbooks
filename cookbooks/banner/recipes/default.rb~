#
# Cookbook Name:: banner
# Recipe:: default
#
# Copyright 2014, YOUR_COMPANY_NAME
#
# All rights reserved - Do Not Redistribute
#
file "/etc/motd" do
owner   "root"
group   "root"
action  :create
content <<-MOTD.gsub(/^ {4}/, '')

==========================^[[1;32mW A R N I N G^[[0m=======================================
This computer system is the property of the Qwinix Inc. It is for authorized use only. 
Unauthorized or improper use of this system may result in administrative disciplinary 
action and/or civil charges/criminal penalties. By continuing to use this system you 
indicate your awareness of and consent to these terms and conditions of use.

LOG OFF IMMEDIATELY if you do not agree to the conditions stated in this warning.
=======================================================================================

  MOTD
end

file "/etc/issue" do
owner   "root"
group   "root"
action  :create
content <<-MOTD.gsub(/^ {4}/, '')

==============================^[[1;32mW A R N I N G^[[0m===============================
This computer system is the property of the Qwinix Inc. It is for authorized use only. 
Unauthorized or improper use of this system may result in administrative disciplinary 
action and/or civil charges/criminal penalties. By continuing to use this system you 
indicate your awareness of and consent to these terms and conditions of use.

LOG OFF IMMEDIATELY if you do not agree to the conditions stated in this warning.
=======================================================================================


  MOTD
end

file "/etc/issue.net" do
owner   "root"
group   "root"
action  :create
content <<-MOTD.gsub(/^ {4}/, '')

==============================^[[1;32mW A R N I N G^[[0m==============================
This computer system is the property of the Qwinix Inc. It is for authorized use only. 
Unauthorized or improper use of this system may result in administrative disciplinary 
action and/or civil charges/criminal penalties. By continuing to use this system you 
indicate your awareness of and consent to these terms and conditions of use.

LOG OFF IMMEDIATELY if you do not agree to the conditions stated in this warning.
======================================================================================

  MOTD
end
