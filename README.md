# Kivy-Buildozer
(
venv) amd@amd-Legion-Y540-15IRH:~/PycharmProjects/pythonProject1$ buildozer android debug deploy run

# Check configuration tokens
# Ensure build layout
# Check configuration tokens
# Read available permissions from api-versions.xml
# Preparing build
# Check requirements for android
# Run 'dpkg --version'
# Cwd None
Система керування пакунками Debian «dpkg», версія 1.21.1 (amd64).
Це вільне програмне забезпечення. Див. умови розповсюдження у
Універсальній суспільній ліцензії GNU версії 2 або пізнішої.
НІЯКІ гарантії не надаються.
# Search for Git (git)
#  -> found at /usr/bin/git
# Search for Cython (cython)
#  -> found at /home/amd/PycharmProjects/pythonProject2/venv/bin/cython
# Search for Java compiler (javac)
#  -> found at /usr/lib/jvm/java-17-openjdk-amd64/bin/javac
# Search for Java keytool (keytool)
#  -> found at /usr/lib/jvm/java-17-openjdk-amd64/bin/keytool
# Install platform
# Run 'git config --get remote.origin.url'
# Cwd /home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android
https://github.com/kivy/python-for-android.git
# Run 'git branch -vv'
# Cwd /home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android
* master 227a7658 [origin/master] Merge pull request #2561 from misl6/release-2022.03.13
# Run '/home/amd/PycharmProjects/pythonProject2/venv/bin/python -m pip install -q  \'appdirs\' \'colorama>=0.3.3\' \'jinja2\' \'six\' \'enum34; python_version<"3.4"\' \'sh>=1.10; sys_platform!="nt"\' \'pep517<0.7.0\' \'toml\''
# Cwd None
# Apache ANT found at /home/amd/.buildozer/android/platform/apache-ant-1.9.4
# Android SDK found at /home/amd/.buildozer/android/platform/android-sdk
# Recommended android's NDK version by p4a is: 19c
# Android NDK found at /home/amd/.buildozer/android/platform/android-ndk-r19c
# Read available permissions from api-versions.xml
# Run '/home/amd/PycharmProjects/pythonProject2/venv/bin/python -m pythonforandroid.toolchain aab -h --color=always --storage-dir="/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/build-arm64-v8a_armeabi-v7a" --ndk-api=21 --ignore-setup-py --debug'
# Cwd /home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android
# Check application requirements
# Compile platform
# Run '/home/amd/PycharmProjects/pythonProject2/venv/bin/python -m pythonforandroid.toolchain create --dist_name=myapp --bootstrap=sdl2 --requirements=python3,kivy --arch arm64-v8a --arch armeabi-v7a --copy-libs --color=always --storage-dir="/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/build-arm64-v8a_armeabi-v7a" --ndk-api=21 --ignore-setup-py --debug'
# Cwd /home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android
/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android/pythonforandroid/toolchain.py:59: DeprecationWarning: distutils Version classes are deprecated. Use packaging.version instead.
  if LooseVersion(cur_ver) < LooseVersion(version):
[INFO]:    Will compile for the following archs: arm64-v8a, armeabi-v7a
[INFO]:    Found Android API target in $ANDROIDAPI: 27
[INFO]:    Available Android APIs are (27)
[INFO]:    Requested API target 27 is available, continuing.
[INFO]:    Found NDK dir in $ANDROIDNDK: /home/amd/.buildozer/android/platform/android-ndk-r19c
[INFO]:    Found NDK version 19c
[INFO]:    Getting NDK API version (i.e. minimum supported API) from user argument
Traceback (most recent call last):
  File "/usr/lib/python3.10/runpy.py", line 196, in _run_module_as_main
    return _run_code(code, main_globals, None,
  File "/usr/lib/python3.10/runpy.py", line 86, in _run_code
    exec(code, run_globals)
  File "/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android/pythonforandroid/toolchain.py", line 1294, in <module>
    main()
  File "/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android/pythonforandroid/entrypoints.py", line 18, in main
    ToolchainCL()
  File "/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android/pythonforandroid/toolchain.py", line 728, in __init__
    getattr(self, command)(args)
  File "/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android/pythonforandroid/toolchain.py", line 141, in wrapper_func
    ctx.prepare_build_environment(user_sdk_dir=self.sdk_dir,
  File "/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/python-for-android/pythonforandroid/build.py", line 423, in prepare_build_environment
    self.ccache = sh.which("ccache")
  File "/home/amd/PycharmProjects/pythonProject2/venv/lib/python3.10/site-packages/sh.py", line 1524, in __call__
    return RunningCommand(cmd, call_args, stdin, stdout, stderr)
  File "/home/amd/PycharmProjects/pythonProject2/venv/lib/python3.10/site-packages/sh.py", line 788, in __init__
    self.wait()
  File "/home/amd/PycharmProjects/pythonProject2/venv/lib/python3.10/site-packages/sh.py", line 845, in wait
    self.handle_command_exit_code(exit_code)
  File "/home/amd/PycharmProjects/pythonProject2/venv/lib/python3.10/site-packages/sh.py", line 869, in handle_command_exit_code
    raise exc
sh.ErrorReturnCode_1: 

  RAN: /usr/bin/which ccache

  STDOUT:


  STDERR:

# Command failed: /home/amd/PycharmProjects/pythonProject2/venv/bin/python -m pythonforandroid.toolchain create --dist_name=myapp --bootstrap=sdl2 --requirements=python3,kivy --arch arm64-v8a --arch armeabi-v7a --copy-libs --color=always --storage-dir="/home/amd/PycharmProjects/pythonProject1/.buildozer/android/platform/build-arm64-v8a_armeabi-v7a" --ndk-api=21 --ignore-setup-py --debug
# ENVIRONMENT:
#     SHELL = '/bin/bash'
#     SESSION_MANAGER = 'local/amd-Legion-Y540-15IRH:@/tmp/.ICE-unix/17249,unix/amd-Legion-Y540-15IRH:/tmp/.ICE-unix/17249'
#     QT_ACCESSIBILITY = '1'
#     COLORTERM = 'truecolor'
#     XDG_CONFIG_DIRS = '/etc/xdg/xdg-ubuntu:/etc/xdg'
#     SSH_AGENT_LAUNCHER = 'gnome-keyring'
#     XDG_MENU_PREFIX = 'gnome-'
#     GNOME_DESKTOP_SESSION_ID = 'this-is-deprecated'
#     TERMINAL_EMULATOR = 'JetBrains-JediTerm'
#     LC_ADDRESS = 'pl_PL.UTF-8'
#     GNOME_SHELL_SESSION_MODE = 'ubuntu'
#     LC_NAME = 'pl_PL.UTF-8'
#     SSH_AUTH_SOCK = '/run/user/1000/keyring/ssh'
#     TERM_SESSION_ID = '0326f8e4-adad-4717-9576-45333a6f84a3'
#     XMODIFIERS = '@im=ibus'
#     DESKTOP_SESSION = 'ubuntu'
#     LC_MONETARY = 'pl_PL.UTF-8'
#     GTK_MODULES = 'gail:atk-bridge'
#     PWD = '/home/amd/PycharmProjects/pythonProject1'
#     XDG_SESSION_DESKTOP = 'ubuntu'
#     LOGNAME = 'amd'
#     XDG_SESSION_TYPE = 'wayland'
#     SYSTEMD_EXEC_PID = '17279'
#     XAUTHORITY = '/run/user/1000/.mutter-Xwaylandauth.0J5CP1'
#     IM_CONFIG_CHECK_ENV = '1'
#     HOME = '/home/amd'
#     USERNAME = 'amd'
#     IM_CONFIG_PHASE = '1'
#     LANG = 'uk_UA.UTF-8'
#     LC_PAPER = 'pl_PL.UTF-8'
#     LS_COLORS = 'rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.webp=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:'
#     XDG_CURRENT_DESKTOP = 'ubuntu:GNOME'
#     VIRTUAL_ENV = '/home/amd/PycharmProjects/pythonProject2/venv'
#     VTE_VERSION = '6800'
#     WAYLAND_DISPLAY = 'wayland-0'
#     GNOME_TERMINAL_SCREEN = '/org/gnome/Terminal/screen/14cb3433_3c95_423e_bd7e_d96b03094cf8'
#     GNOME_SETUP_DISPLAY = ':1'
#     LESSCLOSE = '/usr/bin/lesspipe %s %s'
#     XDG_SESSION_CLASS = 'user'
#     TERM = 'xterm-256color'
#     LC_IDENTIFICATION = 'pl_PL.UTF-8'
#     LESSOPEN = '| /usr/bin/lesspipe %s'
#     USER = 'amd'
#     GNOME_TERMINAL_SERVICE = ':1.100'
#     DISPLAY = ':0'
#     SHLVL = '2'
#     LC_TELEPHONE = 'pl_PL.UTF-8'
#     QT_IM_MODULE = 'ibus'
#     LC_MEASUREMENT = 'pl_PL.UTF-8'
#     XDG_RUNTIME_DIR = '/run/user/1000'
#     PS1 = ('(venv) \\[\\e]0;\\u@\\h: '
 '\\w\\a\\]${debian_chroot:+($debian_chroot)}\\[\\033[01;32m\\]\\u@\\h\\[\\033[00m\\]:\\[\\033[01;34m\\]\\w\\[\\033[00m\\]\\$ ')
#     LC_TIME = 'pl_PL.UTF-8'
#     XDG_DATA_DIRS = '/usr/share/ubuntu:/usr/local/share/:/usr/share/:/var/lib/snapd/desktop'
#     PATH = '/home/amd/.buildozer/android/platform/apache-ant-1.9.4/bin:/home/amd/PycharmProjects/pythonProject2/venv/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:/snap/bin'
#     GDMSESSION = 'ubuntu'
#     DBUS_SESSION_BUS_ADDRESS = 'unix:path=/run/user/1000/bus'
#     LC_NUMERIC = 'pl_PL.UTF-8'
#     OLDPWD = '/home/amd/pycharm'
#     _ = '/home/amd/PycharmProjects/pythonProject2/venv/bin/buildozer'
#     PACKAGES_PATH = '/home/amd/.buildozer/android/packages'
#     ANDROIDSDK = '/home/amd/.buildozer/android/platform/android-sdk'
#     ANDROIDNDK = '/home/amd/.buildozer/android/platform/android-ndk-r19c'
#     ANDROIDAPI = '27'
#     ANDROIDMINAPI = '21'
# 
# Buildozer failed to execute the last command
# The error might be hidden in the log above this error
# Please read the full log, and search for it before
# raising an issue with buildozer itself.
# In case of a bug report, please add a full log with log_level = 2
