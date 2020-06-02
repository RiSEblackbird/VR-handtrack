### Ref.
- [Hand Tracking - Oculus Developer](https://developer.oculus.com/documentation/unity/unity-handtracking/?locale=ja_JP&device=QUEST)

- [Oculus Questでハンドトラッキングアプリの開発　準備編(Unity)](https://note.com/simeis512/n/n195ff642c2d5)

### Assets
- [Oculus Integration | Oculus](https://assetstore.unity.com/packages/tools/integration/oculus-integration-82022)
- [Package Uninstaller](https://assetstore.unity.com/packages/tools/utilities/package-uninstaller-35439)

### Build Settings > Android > Player Settings > Player
- Other Settings
  - Graphics APIs
    DELETE 'Vulkan'
  - Identification
    - Minimum API Level
      CHANGE TO '4.4'(API Level 19以上)

- XR Settings
  - Virtual Reality SDKs
    ADD 'Oculus'