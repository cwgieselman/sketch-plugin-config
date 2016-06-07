# SVGO Compressor Plugin Config File

SVGO Compressor is a Sketch Plugin that compresses SVG assets at the time of export. I tinkered with the config file a bit to give us the output we need to work within the JAMF EE CMS and am passing it along to you!

SVGO Compressor *requires* Sketch 3.8.

## Install

### First Install the plugin
- Download [SVGO Compressor](https://github.com/BohemianCoding/svgo-compressor/archive/master.zip) & unzip it.
- Double click **SVGO Compressor.sketchplugin** to install the Plugin.

### Then grab the new config file
- Download [this repo](https://github.com/cwgieselman/sketch-plugin-config/archive/master.zip) & unzip it.
- Add `svgo.json` to the Sketch's Plugins Directory:
`<user> / Library / Application Support / com.bohemiancoding.sketch3 / Plugins`
- Restart Sketch

## Usage
*Taken from the SVGO Compressor Repo*

Selecting menu items or hitting keys is out of fashion, so SVGO Compressor will compress your SVG assets whenever you export them, without you having to do anything.

You’ll get a message on your document window showing some stats about the process to let you know the compression worked as expected.

If you want your SVG assets uncompressed, you can temporarily disable the Plugin by opening Sketch’s **Preferences › Plugins** and unchecking 'SVGO Compressor'. Alternatively, you can right-click any layer and select **Copy SVG Code**, and that will give you the original, uncompressed code.
