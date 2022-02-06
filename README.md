Simple angular 13 project with working VSCode debugging.  I created this to help discover why debugging in NOT working in this other similar project:  https://github.com/eostermueller/angularFlatTreeExample02

# Setup
Steps to setup this project:

    git clone https://github.com/eostermueller/angularFlatTreeExample01
    npm install
    code .  #to start vscode
    
Then in vscode, open app.component.ts and place a breakpoint on the line with `title = 'tree13c';`:

    import { Component } from '@angular/core';
    
    @Component({
      selector: 'app-root',
      templateUrl: './app.component.html',
      styleUrls: ['./app.component.css']
    })
    export class AppComponent {
      title = 'tree13c';
    }
# Launch/Debug

To launch and debug this project:

* In VSCode, launch "ng serve" on the debug menu.
* the project compiles, 
* the browser launches 
* and after a few seconds control returns to vscode with a 'break' on line `title = 'tree13c';`

