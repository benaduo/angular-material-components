# Angular Material Components

This module exports all the Angular Material components and modules.

## Usage

To use this module in an Angular project, follow these steps:
1. Run `ng add @angular/material` to add Angular Material to your project.
2. Import `MaterialModule` in the `app.module.ts` file as follows:

    ```typescript
    import { MaterialModule } from './path/to/material.module';

    @NgModule({
      imports: [
        BrowserModule,
        MaterialModule
      ],
      ...
    })
    ```

3. Add `MaterialModule` to the imports array in the `@NgModule` decorator of the `app.module.ts` file:

    ```typescript
    import { MaterialModule } from './path/to/material.module';

    @NgModule({
      imports: [
        BrowserModule,
        MaterialModule
      ],
      ...
    })
    ```

For more information on how to use Angular Material in an Angular project, refer to the official documentation: Angular Material.
