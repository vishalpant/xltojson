# xltojson

This Python Package provides the functionality to translate excel data to JSON object.

Excel provides a very intuitive way of organising data using its rich customizations provided by its functions.

Nowadays, many software applications uses JSON (JavaScript Object Notation) to transfer data. If data is in excel format, it can be a cumbersome task to manually translate data to JSON.

## Excel File Format

Each spreadsheet is translated to a python dictionary with key same as the spreadsheet name. The spreadsheet with name "__*Main*__" encloses all the other spreadsheet data.  


Following is a simple code snippet using which a user can translate file containing excel data to a JSON file. 

## Usage: 
 ```
    from xltojson import parse
    parse.translate_excel_to_json(input_excel_file_path, output_json_file_path)
  ```


:peace_symbol:
