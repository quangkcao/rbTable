rbTable
=======

Customizable, sortable, and paginated table - Turn different HTML elements into an interactive table.

/****************
*Plugin: rbTable
*Type:jQuery
*Author: Quang K. Cao 
*Website: www.runbusi.com
*Version 2.0
*10/26/2012
*Licensed under the MIT license.
*
*DESCRIPTION
*Main: Customizable, sortable, highlighted and paginated table - turn different HTML elements into an interactive table.
*Return method: array of selected rows with custome defined attribute or their html content.
*
*DEFAULT VALUES
*METHOD 'init' //initial method
*table:'table',//class of table   
*table_border:[1,'solid','#ccc'],//the border style of table
*               [border-width, border-style, border-color]
*header:'th',//class of header			
*header_bg_color:['transparent','#ccc'],//background of header					
*		[normal state, hover state]
*header_text_color:['',''],//text color in header
*		[normal state, hover state]		
*row:'tr',//class of row that is applied				
*row_bg:['none','#ccc','#666'],//background of row					
*		[normal state, hover state, click state]
*text_color:['','',''],//text color in row
*		  [normal state, hover state, click state]
*pointer_box_border:[1,'dashed','#FFF'],//style for pointer box indicated when user drag mouse over the table						
*                   [border-width, border-style, border-color]
*sort_indicator:['asc', 'desc'],//class identify icon for asc/desc order
*		  [asc class, desc class]
*pagination:['', 'right', 'both'] ,//
*          [limit per page, position 'left' 'right' 'center' of pagination, show both 'top' and 'bottom' of table]]		  
*METHOD 'selected_rows' -> return an array of selected row by a 'attr' attribute
*attr:'name'// attribute of row, for example, 'name' or 'id'.
*			//if attr='html' return html content
****************/