A simple React data grid demo

To use datagrid component, install datagrid package from npm :- 

run command  npm i simple-react-data-grid

###USE 
	
	import DataGrid from 'simple-react-data-grid';
 
    <DataGrid data={data}  metadata={headerData}  styleData={styleData)} />
	
###

"data" = json data to be displayed in table.

"metadata" = json data with values to be shown as column config.
	
	##sample
		metadata =	[
			  {
				'name': ' NAME',
				'key': 'studentName', //should some key's in given "data".
			  },
			  {
				'name': 'ROLL NO',
				'key': 'rollNo',
			  },
			  {
				'name': 'CONFIGURATION NAME',
				'key': 'configurationName',
			  },
			];
}

"styleData"  =  Json data to override default styling.
		
##sample 		
 styleData = {
		  gridWrapper:{
			"width": "100%",
		  },
		  gridTableTD: {
			"color": "red",
			"text-align": "centre",
		  }
  }		

  ##options
		gridwrapper,
		gridContent,
		gridTable,
		gridTableThead,
		gridTableTR,
		gridTableTH,
		gridTableTD,
		gridTableTbody,
		
		
		
	


	
