Demo to help demonstrate the problem described at http://www.opclabs.com/forum/feature-requests-product-improvement-ideas/2523-please-support-packagereference-for-nuget-packages . This project uses `packages.config` and thus the the following files are automatically copied to the output folder by visualstudio in addition to the ones already mentioned in the `.nuspec` as `<references/>`:

* `App_Web_OpcLabs.EasyOpcClassicRaw.amd64.dll`
* `App_Web_OpcLabs.EasyOpcClassicRaw.x86.dll`
* `OpcLabs.BaseLib.xml`
* `OpcLabs.BaseLibForms.xml`
* `OpcLabs.EasyOpcClassic.xml`
* `OpcLabs.EasyOpcUA.xml`

The result is that this project runs without crashing.
