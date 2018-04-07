# VintageVaultAPI
VintageVault - Automatic Vault. (Beta)

VintageVaultMethods holds the needed methods to Work Fully with VintageVault.

Hooking into VintageVault:
------------------------------------------------------------------------------------------------------------------------------------
Instructions: Add to VintageVault in plugin.yml for Depends
To hook into vault, all you have to do is import VintageVault, and use either VintagePermission.<Method> to use Permission Methods, or do VintageEconomy.<Method> to use Economy Methods.

------------------------------------------------------------------------------------------------------------------------------------



Permissions Hook for Permissions Plugins:
------------------------------------------------------------------------------------------------------------------------------------
Step 1: Add VintagePermission file into your plugin and fill in all methods so they work with your Permissions functions correctly

Step 2: Add this in your Main Class of your plugin for Permission Hook:

<code>
public VintagePermission VVPermission() {
    return new VintagePermission(); 
    }
</code>

------------------------------------------------------------------------------------------------------------------------------------



Economy Hook for Economy Plugins:
------------------------------------------------------------------------------------------------------------------------------------
Step 1: Add VintageEconomy file into your plugin and fill in all methods so they work with your Economy functions correctly

Step 2: Add this in the Main Class of your plugin for Economy Hook:

<code>
public VintageEconomy VVEconomy() {
    return new VintageEconomy();
}
</code>

------------------------------------------------------------------------------------------------------------------------------------
