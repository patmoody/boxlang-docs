[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `QueryDeleteColumn`

Deletes a column within a query object.

## Method Signature
```
QueryDeleteColumn(query=[query], column=[string])
```
### Arguments

| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `query` | `query` | `true` | The query object to which the column should be deleted. | |
| `column` | `string` | `true` | The name of the column to delete. | |
|----------|------|----------|-------------|---------|



## Examples

```
QueryDeleteColumn(query=[query], column=[string])
```

## Related
  * [QueryAddColumn](QueryAddColumn.md)
  * [QueryAddRow](QueryAddRow.md)
  * [QueryAppend](QueryAppend.md)
  * [QueryClear](QueryClear.md)
  * [QueryColumnArray](QueryColumnArray.md)
  * [QueryColumnCount](QueryColumnCount.md)
  * [QueryColumnData](QueryColumnData.md)
  * [QueryColumnExists](QueryColumnExists.md)
  * [QueryCurrentRow](QueryCurrentRow.md)
  * [QueryDeleteRow](QueryDeleteRow.md)
  * [QueryEach](QueryEach.md)
  * [QueryEvery](QueryEvery.md)
  * [QueryFilter](QueryFilter.md)
  * [QueryGetCell](QueryGetCell.md)
  * [QueryGetResult](QueryGetResult.md)
  * [QueryKeyExists](QueryKeyExists.md)
  * [QueryMap](QueryMap.md)
  * [QueryNew](QueryNew.md)
  * [QueryPrepend](QueryPrepend.md)
  * [QueryRecordCount](QueryRecordCount.md)
  * [QueryReduce](QueryReduce.md)
  * [QueryRowData](QueryRowData.md)
  * [QuerySetCell](QuerySetCell.md)
  * [QuerySetRow](QuerySetRow.md)
  * [QuerySlice](QuerySlice.md)
  * [QuerySome](QuerySome.md)
  * [QuerySort](QuerySort.md)