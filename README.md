# Appcircle Android Build

This step builds your Android application for the architectures specified in your project. Created files will be .apk, or .aab if you select Android App Bundle in the project configuration.

If your project includes a keystore, this step will generate a signed artifact. If you do not disable the Sign Application step, your artifact will be unsigned and re-signed using the keystore selected in the build configuration.

Required Input Variables
- `$AC_REPOSITORY_DIR`: Cloned git repository path
- `$AC_MODULE`: Project module to be built
- `$AC_VARIANTS`: Specifies build variants
- `$AC_OUTPUT_TYPE`: Output type for your build file(apk or bundle)

Optional Input Variables
- `$AC_PROJECT_PATH`: Specifies the project path
- `$AC_GRADLE_BUILD_EXTRA_ARGS`: Extra arguments passed to build task

Output Variables
- `$AC_APK_PATH`: Path for the generated .apk file
- `$AC_AAB_PATH`: Path for the generated .aab (Android App Bundle) file
