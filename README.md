# rbTable v2.0
###jQuery Plugin
Customizable, sortable, and paginated table - Turn different HTML elements into an interactive table.

***
```javascript
$('.paging_table_wrapper').rbTable({
    table_border :[1,'solid','#99cccc'],
    header_bg_color :['transparent','#6699cc'],
    header_text_color :['#6699cc','#fff',],
    row_bg :['none','#99cccc','#6699cc'],
    text_color :['#6699cc','#6699cc','#FFF'],
    row_border :[1,'solid','#99cccc'],
    pointer_box_border :[3,'solid','#ffcc33'],
    pagination :[3, 'right', 'both']
    });
 ```    
**get array of rows selected with their names by default**
```javascript
    rows=$('.paging_table_wrapper').rbTable('selected_rows');
```     
**get array of rows selected with their HTML contents**
```javascript
    rows=$('.paging_table_wrapper').rbTable('selected_rows','html');
```

### DESCRIPTION

***
#### DEFAULT VALUES
##### init : void - initial method
* **table**:'table',//class of table             
* **table_border**:[1,'solid','#ccc'],//the border style of table
*               [border-width, border-style, border-color]
* **header**:'th',//class of header			
* **header_bg_color**:['transparent','#ccc'],//background of header					
*		[normal state, hover state]
* **header_text_color**:['',''],//text color in header
*		[normal state, hover state]		
* **row**:'tr',//class of row that is applied				
* **row_bg**:['none','#ccc','#666'],//background of row					
*		[normal state, hover state, click state]
* **text_color**:['','',''],//text color in row
*		  [normal state, hover state, click state]
* **pointer_box_border**:[1,'dashed','#FFF'],//style for pointer box indicated when user drag mouse over the table						
*                   [border-width, border-style, border-color]
* **sort_indicator**:['asc', 'desc'],//class identify icon for asc/desc order
*		  [asc class, desc class]
* **pagination**:['', 'right', 'both'] ,//
*          [limit per page, position 'left' 'right' 'center' of pagination, show both 'top' and 'bottom' of table]]	
	  
##### selected_rows : array of selected row by 'attr' attribute - method
* **attr**:'name'// attribute of row, for example, if attr='html' return html content

###Author

***
Quang K. Cao 

http://runbusi.com

###License

***
Licensed under the MIT license.

