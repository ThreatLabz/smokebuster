# SmokeBuster
A tool to detect, analyze, and remediate SmokeLoader infections.

# Compatibility
SmokeBuster has been tested with Windows 7 through Windows 11. The tool has been tested with SmokeLoader 32-bit and 64-bit versions from 2017 - 2022.

# Usage
```
Usage: SmokeDetector.exe v0.1 [options]
        -u    --uninstall            Uninstall Smoke.
        -v    --save-memory          Scan Smoke memory and save matches to disk.
        -p    --delete-tasks         Delete Smoke persistent scheduled tasks.
        -w    --make-sections-rwx    Make Smoke memory sections RWX.
        -c    --close-mutexes        Close Smoke mutexes
        -k    --kill-thread          Terminate a specific Smoke thread ID (separate multiple IDs by commas).
        -K    --killall-threads      Terminate all Smoke threads in explorer.exe
        -s    --suspend-thread       Suspend a specific Smoke thread ID (separate multiple IDs by commas).
        -S    --suspendall-threads   Suspend all Smoke threads in explorer.exe
        -r    --resume-thread        Resume a specific Smoke thread ID (separate multiple IDs by commas))
        -R    --resumeall-threads    Resume all Smoke threads in explorer.exe
        -m    --unmap-memory         Free Smoke memory regions in explorer.exe
        -h    --help                 Show help and exit
```

# Example SmokeLoader Samples
|SHA256|
|:------------------------------------------------------------------|
|50f10e4d8b5379fae2477fcc13bb6403d3d7df441f46bfbeb9218a70cb2cfde8|
|55fbf14b87a98b21febd83146f2d19096370440642121cffbfcc2c26e55f0723|

