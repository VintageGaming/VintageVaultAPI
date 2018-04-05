# VintageVaultAPI
VintageVault - Automatic Vault. (Beta)

VintageVaultApi is holds the needed methods to Work Fully with VintageVault.

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
