## Installation

Wizard runs on angular 2 and is available as an NPM package. You can install ng2-wizard
in your project's directory as usual:

```bash
$ npm install --save @iatec/ng2-wizard
```

Component Wizard(step to step with tabs) for Angular 2.
```
 <wizard orientation="string [landscape|portrait]" hiddenTabs="string [yes|no]" disableTabs="string [yes|no]" disableSteps="Array [number]" hiddenDisableSteps="string [yes|no]" currentStep="int [number]" (stepChange)="onYourFunction($event)">
```

## Example
### Template (.html)
```
 <wizard orientation="portrait">
  <wizard-step>
    <wizard-step-tab>Title of first tab</wizard-step-tab>
    Hello World
  </wizard-step>
 </wizard>
```
### TypeScript (.ts)
Import WizardComponent and WizardStepComponent
```
 import { Ng2WizardModule } from '@iatec/ng2-wizard';
```

Add in your module
```
 @NgModule({   
   imports: [
    Ng2WizardModule,
   ]
 })
```
