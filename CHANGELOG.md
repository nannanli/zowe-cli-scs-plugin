# Changelog

All notable changes to the Secure Credential Store Plug-in for Zowe CLI will be documented in this file.

## `4.1.0`

- Enhancement: Added the `scs revert` command. Use the command to revert securely-stored credentials in your user profiles to be stored in plain text. [#22](https://github.com/zowe/zowe-cli-scs-plugin/issues/22)
- Enhancement: Changed the `scs update` and `scs revert` commands so that they fail if Secure Credential Manager is not enabled. [#23](https://github.com/zowe/zowe-cli-scs-plugin/pull/23)

## `4.0.4`

- Update Keytar dependency to support offline installation for Node.js 13. Thanks @tjohnsonBCM

## `4.0.3`

- Bundle Keytar binaries in NPM package so that plugin can be installed offline. Thanks @awharn, @tjohnsonBCM

## `4.0.2`

- Fix error when loading optional secure fields (e.g., "keyPassphrase" in SSH profile). Thanks @tjohnsonBCM
- Support installing the plugin offline if prebuilt Keytar binaries are bundled. Thanks @tjohnsonBCM
- Fix error when deleting secure profile that has no values stored in credential vault. Thanks @tjohnsonBCM

## `4.0.1`

- Set up Jenkins Pipelines
- Tagged package @zowe-v1-lts

## `4.0.0`

- The Secure Credential Store was contributed to Zowe
