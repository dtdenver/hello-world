Web Development with Bootstrap 4 and Angular 2 Chapter 1
Had to make some changes to make it work
Change es5 to es6 in tsconfig.json, compiler target
Used latest versions of all libraries except for rxjs, had to use 5.0.1
Author's forgot to put lines in app.module.ts, the lines are in the download code not in book
import { AppComponent } from "./app.component"
under @NgModule({
  declarations: [ AppComponent ],
  bootstrap:    [ AppComponent ]
Now working 6/15/2017, but I'd like to figure out where to put the node_modules so I don't repeat it in every project.