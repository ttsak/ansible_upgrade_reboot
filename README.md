# Upgrade and Reboot with ansible

Upgrade all packages on Debian and Redhat family distributions

Reboot after ugrade (only if required) by setting "reboot_for_upgrades"

	--extra-vars="reboot_for_upgrades=true"

Even if you set this flag a reboot will occur only if required by the specific updates that have been installed
