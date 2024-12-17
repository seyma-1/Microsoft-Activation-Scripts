# Microsoft-Activation-Scripts

irm https://get.activated.win | iex


winrm create winrm/config/Listener?Address=*+Transport=HTTP @{Port="5985"}

