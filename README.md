# 🧩 JoFSlash Patches

Patches for [Quora](https://play.google.com/store/apps/details?id=com.quora.android) for use with [Morphe](https://morphe.software).

🌐 Website: https://jofslash.github.io/quora-patches/  
📲 Get Morphe Manager from the official site: https://morphe.software

## ❓ About

- **Remove ads**: hides promoted answers, sponsored posts and Google ads in the feed and on question pages, and blocks requests to ad servers.
- **Disable analytics**: turns off Firebase Analytics, Crashlytics, Firebase Performance and Facebook app events, and stops the advertising ID from being collected.

Tested with Quora 3.2.42 and 3.2.30 from [APKMirror](https://www.apkmirror.com/apk/quora-inc/quora/) (APKM bundle).

### How to use these patches

Click the button below, or manually add this repo url to Morphe Manager: https://github.com/JoFSlash/quora-patches

<a href="https://morphe.software/add-source?github=JoFSlash/quora-patches">
  <img src=".github/assets/add-to-morphe.svg" alt="Add to Morphe" height="48">
</a>

## 🩹 Patches list

<!-- PATCHES_START EXPANDED -->

<!-- Do not modify this section by hand. The patch list is generated when release.yml creates a new release.
     
     If you wish for the patches list to be collapsed, then remove the word 'EXPANDED' from the comment tag above.

     If you wish to manually keep this list updated then remove the PATCHES_START and PATCHES_END 
     comment blocks entirely. -->

#### A list of your patches will automatically be shown here after your first patches release is created.

&nbsp;

<!-- PATCHES_END -->

## 🧑‍💻 Building

Requires JDK 21 and a GitHub token with `read:packages` (see the [Morphe docs](https://github.com/MorpheApp/morphe-documentation/blob/main/docs/morphe-development/1_setup.md)).

```bash
./gradlew buildAndroid
```

The bundle is written to `patches/build/libs/patches-*.mpp`.

## 📜 License

These patches are licensed under the [GNU General Public License v3.0](LICENSE). See [NOTICE](NOTICE).
This project is not affiliated with Quora or with the Morphe project.
