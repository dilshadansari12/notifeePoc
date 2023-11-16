
##Error_pls_look 

npx expo run:android 
› Building app...
Configuration on demand is an incubating feature.
node:internal/process/promises:279
            triggerUncaughtException(err, true /* fromPromise */);
            ^

C:\Users\Dilshad\Desktop\notifee\node_modules\react-native\index.js:14
import typeof AccessibilityInfo from './Libraries/Components/AccessibilityInfo/AccessibilityInfo';
^^^^^^

SyntaxError: Cannot use import statement outside a module
    at Object.compileFunction (node:vm:360:18)
    at wrapSafe (node:internal/modules/cjs/loader:1126:15)
    at Module._compile (node:internal/modules/cjs/loader:1162:27)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1252:10)
    at Module.load (node:internal/modules/cjs/loader:1076:32)
    at Function.Module._load (node:internal/modules/cjs/loader:911:12)
    at Module.require (node:internal/modules/cjs/loader:1100:19)
    at require (node:internal/modules/cjs/helpers:119:18)
    at Object.<anonymous> (C:\Users\Dilshad\Desktop\notifee\node_modules\@notifee\react-native\dist\NotifeeApiModule.js:9:24)
    at Module._compile (node:internal/modules/cjs/loader:1198:14) {
  code: 'INVALID_PLUGIN_IMPORT',
  cause: undefined,
  name: 'PluginError',
  isPluginError: true
}

FAILURE: Build failed with an exception.

* Where:
Script 'C:\Users\Dilshad\Desktop\notifee\node_modules\expo-modules-autolinking\scripts\android\autolinking_implementation.gradle' line: 90

* What went wrong:
A problem occurred evaluating settings 'notifee'.
> Text must not be null or empty

* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 3s
Error: C:\Users\Dilshad\Desktop\notifee\android\gradlew.bat exited with non-zero code: 1
Error: C:\Users\Dilshad\Desktop\notifee\android\gradlew.bat exited with non-zero code: 1
    at ChildProcess.completionListener (C:\Users\Dilshad\Desktop\notifee\node_modules\@expo\spawn-async\build\spawnAsync.js:52:23)
    at Object.onceWrapper (node:events:628:26)
    at ChildProcess.emit (node:events:513:28)
    at ChildProcess.cp.emit (C:\Users\Dilshad\Desktop\notifee\node_modules\cross-spawn\lib\enoent.js:34:29)
    at maybeClose (node:internal/child_process:1100:16)
    at Process.ChildProcess._handle.onexit (node:internal/child_process:304:5)
    ...
    at Object.spawnAsync [as default] (C:\Users\Dilshad\Desktop\notifee\node_modules\@expo\spawn-async\build\spawnAsync.js:17:21)        
    at spawnGradleAsync (C:\Users\Dilshad\Desktop\notifee\node_modules\@expo\cli\build\src\start\platforms\android\gradle.js:72:46)      
    at Object.assembleAsync (C:\Users\Dilshad\Desktop\notifee\node_modules\@expo\cli\build\src\start\platforms\android\gradle.js:52:18)  
    at runAndroidAsync (C:\Users\Dilshad\Desktop\notifee\node_modules\@expo\cli\build\src\run\android\runAndroidAsync.js:36:24)
    at processTicksAndRejections (node:internal/process/task_queues:96:5)
PS C:\Users\Dilshad\Desktop\notifee> 
