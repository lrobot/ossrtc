
fix cipd access https://chrome-infra-packages.appspot.com  error
  add "exit /B 0" to cipd.bat
  add "exit /B 0" to update_depot_tools.bat

mkdir root_ossrtc
cd root_ossrtc
gclient config https://github.com/lrobot/ossrtc.git
gclient sync
