# KingKodePackages: GooglePackages

## What Is This
You can add the Google packages from web instead of donwloading local files which is recomended.

## How to Install
First, make sure you add the following in the main packages manifest.json file:
```json
"scopedRegistries": [
	{
		"name": "package.openupm.com",
		"url": "https://package.openupm.com",
		"scopes": [
			"com.google.android.appbundle",
			"com.google.external-dependency-manager",
			"com.google.play.common",
			"com.google.play.core",
			"com.google.play.review"
		]
	}
]
```

Then, for each package that you want to add, add its deopndency to manifest.json file:
#### External Dependency Manager:
```json
"com.google.external-dependency-manager": "1.2.172"
```

#### Google Play Common:
```json
"com.google.play.common": "1.8.1"
```

#### Google Play Core:
```json
"com.google.play.core": "1.8.1"
```

#### Google Play In-app Review:
```json
"com.google.play.review": "1.8.1"
```

#### Google Play App Bundle:
```json
"com.google.android.appbundle": "1.8.0"
```
