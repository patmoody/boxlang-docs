[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `GetModuleInfo`

Get the module record for a loaded module in BoxLang.

If the module
 doesn't exist, an empty struct is returned.

## Method Signature

```
GetModuleInfo(module=[string])
```

### Arguments


| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `module` | `string` | `true` | The name of the module to get the record for. |  |

## Examples



## Related

  * [ApplicationRestart](./ApplicationRestart.md)
  * [ApplicationStartTime](./ApplicationStartTime.md)
  * [ApplicationStop](./ApplicationStop.md)
  * [BoxAnnounce](./BoxAnnounce.md)
  * [BoxAnnounceAsync](./BoxAnnounceAsync.md)
  * [BoxRegisterInterceptor](./BoxRegisterInterceptor.md)
  * [BoxRegisterRequestInterceptor](./BoxRegisterRequestInterceptor.md)
  * [CallStackGet](./CallStackGet.md)
  * [CreateGUID](./CreateGUID.md)
  * [CreateObject](./CreateObject.md)
  * [CreateUUID](./CreateUUID.md)
  * [DE](./DE.md)
  * [DebugBoxContexts](./DebugBoxContexts.md)
  * [Dump](./Dump.md)
  * [Duplicate](./Duplicate.md)
  * [echo](./echo.md)
  * [EncodeForHTML](./EncodeForHTML.md)
  * [GetApplicationMetadata](./GetApplicationMetadata.md)
  * [GetBaseTemplatePath](./GetBaseTemplatePath.md)
  * [GetBoxContext](./GetBoxContext.md)
  * [GetBoxRuntime](./GetBoxRuntime.md)
  * [GetBoxVersionInfo](./GetBoxVersionInfo.md)
  * [GetClassMetadata](./GetClassMetadata.md)
  * [GetComponentList](./GetComponentList.md)
  * [GetContextRoot](./GetContextRoot.md)
  * [GetCurrentTemplatePath](./GetCurrentTemplatePath.md)
  * [GetFileFromPath](./GetFileFromPath.md)
  * [GetFunctionCalledName](./GetFunctionCalledName.md)
  * [GetFunctionList](./GetFunctionList.md)
  * [GetModuleList](./GetModuleList.md)
  * [GetSystemSetting](./GetSystemSetting.md)
  * [GetTempDirectory](./GetTempDirectory.md)
  * [GetTickCount](./GetTickCount.md)
  * [htmlEditFormat](./htmlEditFormat.md)
  * [IIF](./IIF.md)
  * [Invoke](./Invoke.md)
  * [IsInstanceOf](./IsInstanceOf.md)
  * [JavaCast](./JavaCast.md)
  * [PagePoolClear](./PagePoolClear.md)
  * [Print](./Print.md)
  * [Println](./Println.md)
  * [RunThreadInContext](./RunThreadInContext.md)
  * [SessionInvalidate](./SessionInvalidate.md)
  * [SessionRotate](./SessionRotate.md)
  * [SessionStartTime](./SessionStartTime.md)
  * [Sleep](./Sleep.md)
  * [SystemExecute](./SystemExecute.md)
  * [SystemOutput](./SystemOutput.md)
  * [Throw](./Throw.md)
  * [URLDecode](./URLDecode.md)
  * [URLEncodedFormat](./URLEncodedFormat.md)
  * [writeDump](./writeDump.md)
  * [WriteLog](./WriteLog.md)
  * [WriteOutput](./WriteOutput.md)