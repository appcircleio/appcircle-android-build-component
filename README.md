# Appcircle Android Build

This component will build your Android application with gradle.

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
