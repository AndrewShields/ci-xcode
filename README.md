# CI Xcode

Use GitHub Actions to build a Unity iOS project and upload it to App Store Connect. I'm tired of buying new Apple hardware.

## Setup

### Populate secrets

* See build-and-upload.yaml env
* Example: Unity iOS build.zip
	* Upload a build to Azure blob storage
		* Azure > Storage browser > Blob containers > { BLOBCONTAINER } > build.zip
	* Get the pre-signed url
		* Azure > build.zip > Generate SAS > Generate SAS token and URL

## Run (manual trigger)

* Repo > Actions > Build and upload to App Store Connect > Run workflow
