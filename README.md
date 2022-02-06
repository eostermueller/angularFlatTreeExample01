Simple angular 13 project with working VSCode debugging.  I created this to help discover why debugging in NOT working in this other similar project:  https://github.com/eostermueller/angularFlatTreeExample02

    git clone https://github.com/eostermueller/angularFlatTreeExample01
    npm install
    code .  #to start vscode
    
Then I open app.component.ts and place a breakpoint on the line with `title = 'tree13c';`:

    import { Component } from '@angular/core';
    
    @Component({
      selector: 'app-root',
      templateUrl: './app.component.html',
      styleUrls: ['./app.component.css']
    })
    export class AppComponent {
      title = 'tree13c';
    }

Then when I launch "ng server" on the debug menu, 
* the project compiles, 
* the browser launches 
* and after a few seconds control returns to vscode with a 'break' on line `title = 'tree13c';`

