# Dump

Outputs the contents of a variable (simple or complex) of any type for debugging purposes to a specific output location.

, The available ,{@code output}, locations are: - ,**,buffer,,: The output is written to the buffer, which is the default location. If running on a web server, the output is written to the browser. - ,,console,,: The output is printed to the System console. - ,,{absolute\_file\_path},, The output is written to a file with the specified filename path. ,**

**, The output ,{@code format}, can be either HTML or plain text. The default format is HTML if the output location is the buffer or a web server or a file, otherwise it is plain text for the console.**

## **Method Signature**

Dump(var=\[any], label=\[string], top=\[numeric], expand=\[boolean], abort=\[boolean], output=\[string], format=\[string], showUDFs=\[boolean])**ArgumentsExamplesRelated**[**ApplicationRestart**](applicationrestart.md)[**ApplicationStartTime**](applicationstarttime.md)[**ApplicationStop**](applicationstop.md)[**BoxAnnounce**](boxannounce.md)[**BoxAnnounceAsync**](boxannounceasync.md)[**BoxRegisterInterceptor**](boxregisterinterceptor.md)[**BoxRegisterRequestInterceptor**](boxregisterrequestinterceptor.md)[**CallStackGet**](callstackget.md)[**CreateGUID**](createguid.md)[**CreateObject**](createobject.md)[**CreateUUID**](createuuid.md)[**DE**](de.md)[**DebugBoxContexts**](debugboxcontexts.md)[**Duplicate**](duplicate.md)[**echo**](echo.md)[**EncodeForHTML**](encodeforhtml.md)[**GetApplicationMetadata**](getapplicationmetadata.md)[**GetBaseTagData**](getbasetagdata.md)[**GetBaseTagList**](getbasetaglist.md)[**GetBaseTemplatePath**](getbasetemplatepath.md)[**GetBoxContext**](getboxcontext.md)[**GetBoxRuntime**](getboxruntime.md)[**GetBoxVersionInfo**](getboxversioninfo.md)[**GetClassMetadata**](getclassmetadata.md)[**GetComponentList**](getcomponentlist.md)[**GetContextRoot**](getcontextroot.md)[**GetCurrentTemplatePath**](getcurrenttemplatepath.md)[**GetFileFromPath**](getfilefrompath.md)[**GetFunctionCalledName**](getfunctioncalledname.md)[**GetFunctionList**](getfunctionlist.md)[**GetModuleInfo**](getmoduleinfo.md)[**GetModuleList**](getmodulelist.md)[**GetSystemSetting**](getsystemsetting.md)[**GetTempDirectory**](gettempdirectory.md)[**GetTickCount**](gettickcount.md)[**htmlEditFormat**](htmleditformat.md)[**IIF**](iif.md)[**Invoke**](invoke.md)[**IsInstanceOf**](isinstanceof.md)[**JavaCast**](javacast.md)[**ObjectDeserialize**](objectdeserialize.md)[**ObjectSerialize**](objectserialize.md)[**PagePoolClear**](pagepoolclear.md)[**Print**](print.md)[**Println**](println.md)[**RunThreadInContext**](runthreadincontext.md)[**SessionInvalidate**](sessioninvalidate.md)[**SessionRotate**](sessionrotate.md)[**SessionStartTime**](sessionstarttime.md)[**Sleep**](sleep.md)[**SystemCacheClear**](systemcacheclear.md)[**SystemExecute**](systemexecute.md)[**SystemOutput**](systemoutput.md)[**Throw**](throw.md)[**URLDecode**](urldecode.md)[**URLEncodedFormat**](urlencodedformat.md)[**writeDump**](writedump.md)[**WriteLog**](writelog.md)[**WriteOutput**](writeoutput.md)