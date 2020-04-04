# Issues with xCode
```
 tns platform remove ios; tns platform add ios
 ```


# Issues with Running
```
tns platform clean ios/android
tnsrun ios/android --bundle
```
# ngOnChanges
will excute if one of the value changes
```
ngOnChanges(changes : SimpleChanges){
 if(changes.variable){
 // execute logic
}
```

# Unlock *ngIf 
to unlock ngIf - need to add NativeScriptCommonModule in the module where the component is declared

# ngClass  not-settable
for conditionally setting the styling for same type of elements. for exampele setting the days for calendar - not clickable

# Map on rxjs operators 
to interpret the data in the format we need 
