# angular-cheatsheet

## Components

### CLI
`ng generate component <name>` or `ng g c <name>`
`ng g c <name> --spec=false`

### Decorator


### Projecting content (ngContent)

Project content from the parent component to the child component

app.component.html
```
<app-my-component>
    <p>html content here</p>
</app-my-component>
```

my-component.component.html
```
<div class="container">
    <ng-content></ng-content>
</div>
```
