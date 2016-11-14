***
# ng2stepper
***

Really simple stepper directive for angular2

## How to

- npm install, clone or download .zip
```
npm install ng2stepper
```

- Import ng2stepper in your module:

```
import { ng2stepper } from '{ YOUR_DIR_HERE }/ng2stepper/ng2stepper.component';
```

- Include ng2stepper in ngModule -> declarations:

```
@NgModule({
    imports: [],
    declarations: [
        AppComponent,
        ng2stepper
    ],
    providers: [],
    bootstrap: [ AppComponent ]
})
```

- Add stepper to desired page:

```
<ng2stepper elements="4" active="2"></ng2stepper>
```

- Add stepper in a table row:
 
```
<ng2stepper elements="4" active="2" size="table"></ng2stepper>
```
***

