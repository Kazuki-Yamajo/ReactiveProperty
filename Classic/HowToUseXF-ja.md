# Xamarin.Forms��ReactiveProperty���C���X�g�[��������@

## �菇1. �v���W�F�N�g�̍쐬
Cross Platform App (Xamarin)��V�K�쐬���܂��B
�����ł́AXamarin.Forms��PCL�̋�̃A�v�����쐬���܂��B�v���W�F�N�g����HowToUseRp�Ƃ������O�ō쐬���܂����B

![Create project](Images/xf-howtouserp-createproject.png)

## �菇2. .NET Standard �v���W�F�N�g�̍쐬

.NET Standard �̃N���X���C�u�����v���W�F�N�g���쐬���܂��B
�����ł́AHowToUseRp.NetStandard�Ƃ������O�ō쐬���܂����B

HowToUseRp.NetStandard�v���W�F�N�g�̃v���p�e�B���J���ċK��̖��O��Ԃ�HowToUseRp�ɕύX���܂��B
�^�[�Q�b�g�t���[�����[�N��.NETStandard 1.3�ȏ�ɂȂ��Ă��邱�Ƃ��m�F���Ă��������B

## �菇3. �Q�Ƃ̒ǉ�

Xamarin.Forms��ǉ��o����悤�Ƀv���W�F�N�g�t�@�C����ύX���܂��B
HowToUseRp.NetStandard�v���W�F�N�g���E�N���b�N���āuHowToUseRp.NetStandard.csproj ��ҏW����v��I�����܂��B

�����āAPackageTargetFallback�^�O��ǉ����܂��B

```xml
<Project Sdk="Microsoft.NET.Sdk">

  <PropertyGroup>
    <TargetFramework>netstandard1.4</TargetFramework>
    <RootNamespace>HowToUseRp</RootNamespace>
    <PackageTargetFallback>portable-net46+uap</PackageTargetFallback>
  </PropertyGroup>

</Project>
```

HowToUseRp.NetStandard�v���W�F�N�g�Ɉȉ��̎Q�Ƃ�ǉ����܂��B

- Xamarin.Forms

�S�Ẵv���W�F�N�g��Xamarin.Forms���ŐV�̈���ɍX�V���܂��B

HowToUseRp.NetStandard�v���W�F�N�g��HowToUseRp.Android�v���W�F�N�g��HowToUseRp.iOS�v���W�F�N�g��HowToUseRp.UWP�v���W�F�N�g��ReactiveProperty�̍ŐV��(v4.0.0�ȍ~)��ǉ����܂��B

## �菇4. PCL����.NET Standard�v���W�F�N�g�փR�[�h�̈ړ�

HowToUseRp.NetStandard�v���W�F�N�g��Class1.cs���폜���āAHowToUseRp�v���W�F�N�g�̃\�[�X��S��HowToUseRp.NetStandard�v���W�F�N�g�ɃR�s�[���܂��B
�ړ�����R�[�h�͈ȉ��̂��̂ɂȂ�܂��B

- App.xaml
- App.xaml.cs
- MainPage.xaml
- MainPage.xaml.cs

HowToUseRp�v���W�F�N�g���폜���āAHowToUseRp.NetStandard�v���W�F�N�g���ȉ��̃v���W�F�N�g�̎Q�Ƃɒǉ����܂��B

- HowToUseRp.Android
- HowToUseRp.iOS
- HowToUseRp.UWP

## �菇5. ���s���ē���m�F

�e�v���W�F�N�g���N�����邩�m�F���܂��B

## �菇6. �R�[�h�������܂��傤

�C���X�g�[�������������̂ŁAReactiveProperty���g�����R�[�h�������܂��傤�I
