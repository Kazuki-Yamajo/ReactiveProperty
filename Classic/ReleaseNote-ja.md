# �����[�X�m�[�g

## v4.0.0-pre1
### �X�V
- System.Reactive v4.0.0-preview00001 �ɍX�V

### �ύX
- ReactiveProperty �� internal �ȃR���X�g���N�^�� public �ɕύX���܂���
- ReadOnlyReactiveProperty �� internal �ȃR���X�g���N�^�� public �ɕύX���܂���

### �j��I�ύX
- SerializeHelper �̍폜
- .NET Standard 1.1 ���� .NET Standard 1.3 �ɕύX
    - .NET Framework 4.5 ��Ή��v���b�g�t�H�[������O���܂���
	- Windows store app ��Ή��v���b�g�t�H�[������O���܂���

## v3.6.0
### �j��I�ύX
- iOS������SetBinding���\�b�h��SetBindingXXXXX(�Ώۂ̃N���X��)�ɕύX���܂���

### Add
- AsyncReactiveCommand#Subscribe ���\�b�h�Ɉ����Ȃ��o�[�W������ǉ����܂���
- ReactiveCommand#Subscribe ���\�b�h�Ɉ����Ȃ��o�[�W������ǉ����܂���

## v3.5.0
### �j��I�ύX
- ObserveEveryValueChanged�g�����\�b�h�̖��O��Ԃ�Extensions����ObjectExtensions�ύX���܂���.

### �ǉ�
- Refresh���\�b�h��IFilteredReadOnlyObservableCollection�ɒǉ����܂���.

## v3.4.0
### �X�V
- Rx 3.1.1�ɍX�V���܂���

### �ǉ�
- DependencyObject��ObserveDependencyProperty�g�����\�b�h��ǉ����܂����B(UWP��WPF)
- DependencyObject��ToReadOnlyReactiveProperty�g�����\�b�h��ǉ����܂����B(UWP��WPF)
- DependencyObject��ToRReactiveProperty�g�����\�b�h��ǉ����܂����B(UWP��WPF)

## v3.3.0

- Rx 3.1.0�ɃA�b�v�f�[�g���܂���
- UWP�̃r�w�C�r�A��v2.0.0�ɃA�b�v�f�[�g���܂���

## v3.2.0

### �ǉ�

- iOS�p��`SetBinding`���\�b�h��ǉ����܂����B

## v3.1.0

- VB��PropertySelector�̃T�|�[�g

## v3.0.0

### �X�V
- Reactive Extensions 3.0�ɍX�V���܂����B

## v2.9
### �ǉ�
- AsyncReactiveCommand��ǉ����܂����B

## v2.8
### �ǉ�
- disposeElement������ToReadOnlyReactiveCollection���\�b�h�ɒǉ����܂����B�f�t�H���g�l��true�i���܂łƓ��������j�ł��B

### �ύX
- �f�t�H���g�̃X�P�W���[���쐬���W�b�N��ύX���܂����B�R���\�[���A�v���P�[�V�����ł���O���o���Ɏg���܂��B


## v2.7.2

### Add
- ObserveEveryValueChanged�g�����\�b�h��ǉ����܂����B(WPF�̂�)

## v2.7.1
### �ǉ�
- IO<bool>#Inverse�g�����\�b�h��ǉ����܂����B

## v2.7
### �ǉ�
- BusyNotifier��ǉ����܂����B

## v2.6
### �ύX
- �f�t�H���g�̃X�P�W���[����UIDispatcherScheduler����ReactivePropertyScheduler�ɕύX���܂���
- UWP�g�p����BehaviorSDK�ł͂Ȃ�Microsoft.Xaml.Behaviors.Uwp.Managed���Q�Ƃ���悤�ɕύX���܂���

## v2.5

### Add
- ForceNotify/ForceValidate���\�b�h��ǉ����܂���

## v2.4.2

### �o�O�t�B�b�N�X

- ToReactivePropertyAsSynchronized���\�b�h��ignoreValidationErrorValue�������Ȃ������o�O���C��

## v2.4.1

### �o�O�t�B�b�N�X

- ReadOnlyReactiveCollection��Dispose���ɃR���N�V�����̗v�f��Dispose���Ă΂�Ȃ��P�[�X��������ɑΉ�

## v2.4.0

### �ǉ�

- iOS������UIView��ReactiveProeprty/ReactiveCommand���o�C���h����g�����\�b�h��ǉ����܂���

## v2.3.1

### �ύX

- IReadOnlyReactiveProperty�̌^������out�ɕύX���܂����B

## v2.3

### �p�t�H�[�}���X

- ReactiveProperty�N���X�̃R���X�g���N�^�̏������\�����P���܂����B

### �ǉ�

- Xamarin.Mac�̃v���t�@�C����ǉ����܂���
- .NET Framework 4.6�̃o�C�i�����쐬���܂���

## v2.2.8

### �ύX

- ReactiveProperty��ReadOnlyReactiveProperty�̎����C���^�[�t�F�[�X��ύX���܂����B Issue #11.

## v2.2.7

### �ύX

- IFilteredReadOnlyObservableCollection�̓���������ύX

## v2.2.6

### �ǉ�

- ReactiveCollection�N���X��AddRangeOnScheduler���\�b�h��ǉ�.

## v2.2.5

### �X�V

- System.Windows.Interactivity�A�Z���u���ւ̎Q�Ƃ��X�V.

## v2.2.4

### �o�O�t�B�b�N�X

- FilteredReadOnlyObservableCollection�ɍ폜���̃C���f�b�N�X�Ǘ��̖����C��
- FilteredReadOnlyObservableCollection�ɒl�̓���ւ����̃C���f�b�N�X�Ǘ��̖����C��

## v2.2.3

### �o�O�t�B�b�N�X

- ReadOnlyReactiveCollection��Remove����Converter�����s����Ă��������C��

## v2.2.2

### �o�O�t�B�b�N�X

- FilteredReadOnlyObservableCollection�̏����������ŃC���f�b�N�X�̊Ǘ��ɖ�肪�������̂��C��

## v2.2.1

### �o�O�t�B�b�N�X

- ReadOnlyReactiveProperty�̃R���X�g���N�^�ŕ�����Subscribe���\�b�h���Ăяo���Ă����s����C�����܂����B

## v2.2

### �j��I�ύX

- ObserveElementReactiveProperty �g�����\�b�h���폜���܂����B

### Add

- ObserveElementObservableProperty �g�����\�b�h��ǉ����܂����B

## v2.1.8

### �ǉ�

- Helpers���O��ԂɃ��A���^�C���ɃR���N�V�����̗v�f���t�B���^�����O����R���N�V���� FilteredReadOnlyObservableCollection<T> ��ǉ����܂����B

## v2.1.7

### �o�O�t�B�b�N�X

- ReadOnlyReactiveProperty �� BehaviorSubject<T> ���\�[�X�ɍ�������� BehaviorSubject<T> ����ŏ��ɔ��s�����l�������l�Ƃ��Ďg���Ă��Ȃ������s����C�����܂����B

## v2.1.6

### �ǉ�

- ObservableCollection �� ReadOnlyObservableCollection �̗v�f�� ReactiveProperty �̕ύX���Ď����� ObserveElementReactiveProperty �g�����\�b�h���������܂����B
- ObservableCollection �� ReadOnlyObservableCollection �̗v�f�� PropertyChanged �C�x���g���Ď����� ObserveElementPropertyChanged �g�����\�b�h���������܂����B
- �ǂݎ���p�� ReactiveProperty �ł��� ReadOnlyReactiveProperty<T> ���������܂����BIObservable<T> ���� ToReadOnlyReactiveProperty �g�����\�b�h�Ő����ł��܂��B

### �j��I�ύX

- INotifyCollectionChanged �̊g�����\�b�h�Ƃ��Ē񋟂���Ă��� ObserveElementProperty ���\�b�h�̃A�N�Z�V�r���e�B�� internal �ɂ��܂����B

## v2.1.5

### �ǉ�

- IEnumerable����ReadOnlyReactiveCollection���쐬����g�����\�b�h��ǉ����܂����B

## v2.1.4

- ����

## v2.1.3

### �j��I�ύX

- ObserveElementProperty �Œl�ɕύX���������C���X�^���X���ʒm�ł���悤�ɂ��܂����B

## v2.1.2

### �ǉ�

- ObservableCollection �� ReadOnlyObservableCollection �̗v�f�̃v���p�e�B�ύX���Ď����� ObserveElementProperty �g�����\�b�h���������܂����B
- INotifyCollectionChanged �ɑ΂��� ObserveXxxChanged �g�����\�b�h��ǉ����܂����B

### �ύX

- ToReadOnlyReactiveCollection �g�����\�b�h����Q�ƌ^������������܂����B

## v2.1.1

### �ύX

- SynchronizationContext.Current �� null �̏ꍇ�� UIDispatcherScheduler ������������Ɣ��������O��ύX���܂����B 

## v2.1.0

### �ǉ�

- ReadOnlyReactiveCollection��ReadOnlyObservableCollection����쐬�ł���悤�ɂ��܂���
	- readOnlyObservableCollectionInstance.ToReadOnlyReactiveCollection(x => CreateViewModel(x))

### �ύX

- ReadOnlyReactiveCollection��Dispose���\�b�h���Ăяo�����Ƃ��ɁA�R���N�V���������̃C���X�^���X�ɑ΂��Ă�Dispose���ĂԂ悤�ɂ��܂���

## v2.0.1

### �ύX

- BooleanNotifier�N���X��INotifyPropertyChanged���������܂����B

## v2.0.0

### �j��I�ύX

- ���O��Ԃ� Codeplex.Reactive ���� Reactive.Bindings �ɕς��܂����B
- ReactiveProperty#ObserveHasError ���\�b�h��ObserveHasErrors�ɕύX���Ă��������B

### �񐄏�

- EventToReactive��񐄏��ɂ��܂����BEventToReactiveProperty��EventToReactiveCommand���g���Ă��������B

### �ύX�_

- ReadOnlyReactiveProperty���v�f���폜����Ƃ���Dispose���\�b�h���ĂԂ悤�ɂȂ�܂����B
- CountNotifier�N���X��INotifyPropertyChanged���������܂����B

### �ǉ�

- Xamarin.Android�p�̋@�\��ǉ����܂���
    - View�N���X��SetBinding�g�����\�b�h��ǉ����܂����B
    - IObservable<T>��SetCommand�g�����\�b�h��ǉ����܂����B
