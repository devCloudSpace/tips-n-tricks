
-   Crypting Known Malware with Software Protectors

    -   One such open source crypter, called Hyperion  
    
        `cp /usr/share/windows-binaries/Hyperion-1.0.zip  
        unzip Hyperion-1.0.zip  
        cd Hyperion-1.0/  
        i686-w64-mingw32-g++ Src/Crypter/*.cpp -o hyperion.exe  
        cp -p /usr/lib/gcc/i686-w64-mingw32/5.3-win32/libgcc_s_sjlj-1.dll .  
        cp -p /usr/lib/gcc/i686-w64-mingw32/5.3-win32/libstdc++-6.dll .  
        wine hyperion.exe ../backdoor.exe ../crypted.exe`

veil framework , wip