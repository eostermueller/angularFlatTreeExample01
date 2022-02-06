Simple angular 13 project with working VSCode debugging.

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

