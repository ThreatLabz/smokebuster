# SmokeBuster <img src="./assets/smokebuster.png" alt="logo" width="20"/>

A tool to detect, analyze, and remediate SmokeLoader infections.

# Compatibility
SmokeBuster has been tested with Windows 7 through Windows 11. The tool has been tested with SmokeLoader 32-bit and 64-bit versions from 2017 - 2022.

# Usage
```
Usage: SmokeDetector.exe v0.1 [options]
        -u    --uninstall            Uninstall Smoke
        -v    --save-memory          Scan Smoke memory and save matches to disk
        -p    --delete-tasks         Delete Smoke persistent scheduled tasks
        -w    --make-sections-rwx    Make Smoke memory sections PAGE_EXECUTE_READWRITE
        -c    --close-mutexes        Close Smoke mutexes
        -k    --kill-thread          Terminate a specific Smoke thread ID (separate multiple IDs by commas)
        -K    --killall-threads      Terminate all Smoke threads in explorer.exe
        -s    --suspend-thread       Suspend a specific Smoke thread ID (separate multiple IDs by commas)
        -S    --suspendall-threads   Suspend all Smoke threads in explorer.exe
        -r    --resume-thread        Resume a specific Smoke thread ID (separate multiple IDs by commas)
        -R    --resumeall-threads    Resume all Smoke threads in explorer.exe
        -m    --unmap-memory         Free Smoke memory regions in explorer.exe
        -h    --help                 Show help and exit
```

# Example SmokeLoader Samples
|SHA256|Version|
|:------------------------------------------------------------------|--|
|c78bc4fb8955940b3ac9b52cb16744a61f8bdaf673fd64fc106465241c56cc6c| 2022|
|7377efde4e4e86650ab8495f57ab4a76d4f8efe31e2962305b8c42a6cee70454| 2020|
|d5efd66f54dce6b51870e40a458fa30de366a2982ab2f83dddff5cb3349f654d| 2019|
|5727c2cd54b8408ca0f8e943cad61027a2c3d51da64f2f1224a6b9acc4820f8e| 2018|
|32ba1f3b96cf77a08c041d4983d6afa7db8e1948d27d6a8dd55b7bb95e493189| 2017|


