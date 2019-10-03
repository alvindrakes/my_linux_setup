# My Ubuntu Linux setup

1. Android studio setup 
    * > sudo apt install qemu-kvm
    * > sudo chown [your-username] /dev/kvm 
    * install android studio tar file https://developer.android.com/studio 
    * extract file in desired directory & go to bin, then run 
        > ./studio.sh 
    * create desktop entry

2. VsCode 
    * install vscode from website 
        https://code.visualstudio.com/download
    * install extensions from github textfile 
        https://github.com/alvindrakes/my_vscode_extensions/blob/master/vscode_extensions_installation_command.txt

3. Flutter setup 
    * download flutter SDK
        https://flutter.dev/docs/get-started/install/linux
    * extract file in desired directory 
    * go to that directory, then in terminal, type 
        > sudo chown -R [YOUR_USERNAME] flutter
        
        https://stackoverflow.com/questions/58087025/permission-error-when-creating-flutter-project
    * Go to android studio setting, setup flutter SDK path 

4. Install Java
    * > sudo apt install openjdk-11-jre-headless
        
        https://linoxide.com/linux-how-to/install-java-ubuntu/ 