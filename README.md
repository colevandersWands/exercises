option 1:
```
Boolean( 5 - 4.5 ).toString();
 \       \  |  /         /
  \       \ | /        /  
   \   (num, 0.5)    /
    \     /        /
     \   /       /
 (bool, true)  /
       \     /
         \ /
     (str, 'true')
```

option 2:
```
Boolean( 5 - 4.5 ).toString();
        |-------|
|----------------|
|--------------------------|
 \       \  |  /         /
  \       \ | /        /  
   \   (num, 0.5)    /
    \     /        /
     \   /       /
 (bool, true)  /
       \     /
         \ /
     (str, 'true')
```

option 3:
```
Boolean( 5 - 4.5 ).toString();
        |-------|               -> (num, .5)
|----------------|              -> (bool, true)      
|----------------------------|  -> (str, 'true')
```

option 4:
```
Boolean( 5 - 4.5 ).toString();
-----------------------------
Boolean( num, .5 ).toString();              
(-- bool, true --).toString();
(------- str, 'true' -------);
```

option 5:
```
Boolean( 5 - 4.5 ).toString();
-----------------------------
Boolean(   0.5   ).toString();    
-----------------------------
(      true      ).toString();
-----------------------------
(           "true"          );
```

option 6:
```js
Boolean( 5 - 4.5 ).toString();
//--------------------------//
Boolean(   0.5   ).toString();    
//--------------------------//
(      true      ).toString();
//--------------------------//
(           "true"          );
```






# exercises

## 1:

__Error-Log__  

__JS-Reference__

___

## 2:

__Expansions__  

___

## 3:

__Strategy-Analysis__

__Data-Strategies__

___

## 4: 

__Create-Solutions__

__Debug-Offs__

___

## 5: 

__Reading-Lodash__

__TDD__

___

## 6:

__Sol. Des - App Design__

__Sol. Des - User Focused Dev__

__Sol. Des - Collaboration__
