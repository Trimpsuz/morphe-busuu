# 👋🧩 Busuu patches

Morphe patches for [Busuu](https://busuu.com/)

## ❓ About

Patches your status to premium and removes ads. Unlocks virtually every premium feature, including premium plus features This is a continuation of [boosuu](https://github.com/trimpsuz/boosuu), as morphe patches.

## 🩹 Patches list

<!-- PATCHES_START EXPANDED -->

<!-- Do not modify this section by hand. The patch list is generated when release.yml creates a new release.
     
     If you wish for the patches list to be collapsed, then remove the word 'EXPANDED' from the comment tag above.

     If you wish to manually keep this list updated then remove the PATCHES_START and PATCHES_END 
     comment blocks entirely. -->

#### A list of your patches will be automatically shown here after your first patches release is created.

&nbsp;

## 🧑‍💻 Usage

To develop and release Morphe Patches using this template, some things need to be considered:

- Development starts in feature branches. Once a feature branch is ready, it is squashed and merged into the `dev` branch
- The `dev` branch is merged into the `main` branch once it is ready for release
- Semantic versioning is used to version Morphe Patches.
- [Semantic commit](https://kapeli.com/cheat_sheets/Semantic_Commits.docset/Contents/Resources/Documents/index) messages are used for commits
- Commits on the `dev` branch and `main` branch are automatically released
  via the [release.yml](.github/workflows/release.yml) workflow, which is also responsible for generating the changelog
  and updating the version of Morphe Patches. It is triggered by pushing to the `dev` or `main` branch.
  The workflow uses the `publish` task to publish the release of Morphe Patches.
- The `buildAndroid` task is used to build Morphe Patches so that it can be used on Android.


## 🤓 Tips
- See the [patcher documentation](https://github.com/MorpheApp/morphe-patcher/blob/main/docs/1_patcher_intro.md)
  for more examples of creating patches and fingerprints.
- Do not manually edit any generated files such as: `patches-list.json`, `patches-bundle.json`, `CHANGELOG.md`.
  These files will be automatically updated in the release action.
- Do not force push any semantic release commits or you will break the release. To 'redo' the last release then:
    - Git drop the last dev/main semantic release commit you want to redo.
    - Delete the release from the release area of this repo and delete the tag
    - Make any other changes you wish to do
    - Force push dev/main branch
    - A new replacement release will be created by `release.yml`


## 📚 Everything else

Optionally you can include a button/link in this readme that users can click to add your
patches to Morphe (update the links below after creating your new patches repo):

<!-- The patches end tag is intentionally placed here so the first release will cleanup 
     this readme of all developer instructions above. -->
<!-- PATCHES_END -->

#### How to use these patches

Click here to add these patches to Morphe: https://morphe.software/add-source?github=trimpsuz/morphe-busuu

Or manually add this repository url as a patch source in Morphe: https://github.com/trimpsuz/morphe-busuu

### 📙 Contributing

Thank you for considering contributing to Busuu Morphe Patches.  
You can find the contribution guidelines [here](CONTRIBUTING.md).

### 🛠️ Building

To build Busuu Morphe Patches,
you can follow the [Morphe documentation](https://github.com/MorpheApp/morphe-documentation).

## 📜 License

Busuu Morphe Patches are licensed under the [GNU General Public License v3.0](LICENSE)