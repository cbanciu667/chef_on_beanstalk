# cos_windows_base

Cookbook for integrating chef with AWS Beanstalk Windows instances
requirements by using Powershell and .ebextensions:
- Beanstalk env variables created manually or via Cloud Formation stacks
- Windows instances
- check the yaml after ANY change with http://www.yamllint.com/
- powershell

target:
- further customisation for Beanstalk instances
- maximum converge speed
- an chef removal cmd script will be added that will be launched at shutdown/reboot

by Cosmin Banciu, v 1.0.1, 2018
