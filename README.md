# Local Tours Rundeck Plugin

This plugin loads tours from a configured location on the file system.


#### Plugin Properties

*(Required)* Set the base director:
`framework.plugin.TourLoader.localtours.tourEndpoint=/opt/tours`

*(Optional)* Set the tour manifest file name (default is `tour-manifest.json`):  
`framework.plugin.TourLoader.localtours.tourManifestName=tour-manifest.json`

*(Optional)* Set the sub path in which the tour files exist (default is `tours`):  
`framework.plugin.TourLoader.localtours.toursSubDir=tours`