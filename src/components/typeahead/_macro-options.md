| Name          | Type                                 | Required | Description                                                              |
| ------------- | ------------------------------------ | -------- | ------------------------------------------------------------------------ |
| id            | string                               | true     | ID for the input                                                         |
| classes       | string                               | false    | CSS classes to apply to the wrapping element                             |
| content       | TypeaheadContent                     | true     | Aria and results messaging content                                       |
| typeaheadData | string                               | true     | URL of the JSON file with the typeahead data that needs to be searched   |
| inputClasses  | string                               | false    | CSS classes to apply to the input                                        |
| name          | string                               | true     | Name attribute for the input                                             |
| label         | `Label` [_(ref)_](/components/label) | true     | Label config for the input                                               |
| autocomplete  | string                               | true     | Autocomplete attribute used to override the browsers native autocomplete |
| error         | `Error` [_(ref)_](/components/error) | false    | Configuration for validation errors                                      |
