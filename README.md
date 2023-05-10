# ktor_websocket_rejectedexecution

On Windows 11, In IntelliJ IDEA 2023.1.1 (Ultimate Edition) Build #IU-231.8770.65, built on April 27, 2023
- open project
- Start Main

In Postman
- create a new websocket request
- In the server url field enter: ws://localhost:8080/ws
- click connect
- send a message

In Intellij: 
- Exit

See: 
```
"C:\Program Files\Amazon Corretto\jdk17.0.4_9\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2023.1.1\lib\idea_rt.jar=22414:C:\Program Files\JetBrains\IntelliJ IDEA 2023.1.1\bin" -Dfile.encoding=UTF-8 -classpath C:\src\ktor_websocket_rejectedexecution\build\classes\kotlin\main;C:\src\ktor_websocket_rejectedexecution\build\resources\main;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-server-websockets-jvm\2.3.0\3fbca730a6352a4f7572815bc8f4b06b0c716c36\ktor-server-websockets-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-server-netty-jvm\2.3.0\bfdbe066e5b708f8194d11bc58e8e4c2e8a9b9dc\ktor-server-netty-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-server-core-jvm\2.3.0\acc3db8d9e8cee58d6f31329230bad078e1483e8\ktor-server-core-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.8.21\67f57e154437cd9e6e9cf368394b95814836ff88\kotlin-stdlib-jdk8-1.8.21.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\ch.qos.logback\logback-classic\1.2.11\4741689214e9d1e8408b206506cbe76d1c6a7d60\logback-classic-1.2.11.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.8.21\7473b8cd3c0ef9932345baf569bc398e8a717046\kotlin-stdlib-jdk7-1.8.21.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlinx\kotlinx-coroutines-jdk8\1.6.4\5bc4b0bf6fd90fc190fd2f17e919c74c6274cb71\kotlinx-coroutines-jdk8-1.6.4.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.slf4j\slf4j-api\1.7.36\6c62681a2f655b49963a5983b8b0950a6120ae14\slf4j-api-1.7.36.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.8.21\d749cd5ae25da36d06e5028785038e24f9d37976\kotlin-stdlib-common-1.8.21.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-codec-http2\4.1.91.Final\4ee7027e1653c6ee3f843191e0d932f29e8e14e1\netty-codec-http2-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.eclipse.jetty.alpn\alpn-api\1.1.3.v20160715\a1bf3a937f91b4c953acd13e8c9552347adc2198\alpn-api-1.1.3.v20160715.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport-native-kqueue\4.1.91.Final\a553e0a0b25f2ba6d401a6d29aae8a34b2914098\netty-transport-native-kqueue-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport-native-epoll\4.1.91.Final\29ab7a317bdc97659e7614a66e213fc0087101db\netty-transport-native-epoll-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-reflect\1.8.10\1e90b778ea4669b6bcbfaca57313665ddd804779\kotlin-reflect-1.8.10.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\com.typesafe\config\1.4.2\4c40a633e7994cfb0354244efb6d03fcb11c3ecf\config-1.4.2.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.8.21\43d50ab85bc7587adfe3dda3dbe579e5f8d51265\kotlin-stdlib-1.8.21.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\ch.qos.logback\logback-core\1.2.11\a01230df5ca5c34540cdaa3ad5efb012f1f1f792\logback-core-1.2.11.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-websocket-serialization-jvm\2.3.0\16a67e2d9845b5b294970615a56f2e3bc6848ee1\ktor-websocket-serialization-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-websockets-jvm\2.3.0\c7b782932461bdc398c21489e9f6ab0977bdfa3e\ktor-websockets-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlinx\kotlinx-coroutines-core-jvm\1.6.4\2c997cd1c0ef33f3e751d3831929aeff1390cb30\kotlinx-coroutines-core-jvm-1.6.4.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-server-host-common-jvm\2.3.0\932db6d8db450bb6d5b1b77bb254b400637f5038\ktor-server-host-common-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-codec-http\4.1.91.Final\4519d2ff470941f0086214b19c9acf992868112f\netty-codec-http-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-handler\4.1.91.Final\444cf41e4fe28c47ffebba5e77b9458a12f938a1\netty-handler-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-codec\4.1.91.Final\3044b8e325e33f72c96ac1ea51dda85bef090cc0\netty-codec-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport\4.1.91.Final\c2f6bd7143194ca842b535546a405c06aa993934\netty-transport-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-buffer\4.1.91.Final\d8f180291c3501e931968ca7e40ae0323c4eacee\netty-buffer-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-common\4.1.91.Final\93e5056462a242718e7689d81180d125c79d7723\netty-common-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport-classes-kqueue\4.1.91.Final\35bf9dd51bcb97debb9296f1f48cc265c32d3ce5\netty-transport-classes-kqueue-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport-native-unix-common\4.1.91.Final\80990b5885b8b67be096d7090cba18f05c67120e\netty-transport-native-unix-common-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport-classes-epoll\4.1.91.Final\afd5f7899a61b8f7447b6a2ee06e9b56c9bdacc3\netty-transport-classes-epoll-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-serialization-jvm\2.3.0\b5fdc749cc2cf7429a21ac94189ec79ec4c673b9\ktor-serialization-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-events-jvm\2.3.0\14d7a9f41bf7c5b278ece6a000e8d5e6b6e8fb35\ktor-events-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-http-jvm\2.3.0\3e0f918edcaf0633b9270634993bde0173b326b5\ktor-http-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-utils-jvm\2.3.0\d56ce8d24414fdea24160fc3ba19118c52f4c2b\ktor-utils-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.netty\netty-resolver\4.1.91.Final\4725d117d4b71ef0e743aa79062489b45472b26\netty-resolver-4.1.91.Final.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-http-cio-jvm\2.3.0\d947af86e1d1798c94788ae4f7cfe8a6a1eb6e4a\ktor-http-cio-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-io-jvm\2.3.0\edf51e6b94f6f35a39891b6e3ca57066b326ef52\ktor-io-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\io.ktor\ktor-network-jvm\2.3.0\e96ba7ede31805ee4cc415753fb4923cd0d3777\ktor-network-jvm-2.3.0.jar;C:\Users\me\.gradle\caches\modules-2\files-2.1\org.fusesource.jansi\jansi\2.4.0\321c614f85f1dea6bb08c1817c60d53b7f3552fd\jansi-2.4.0.jar com.example.ApplicationKt
2023-05-10 12:20:35.519 [main] INFO  ktor.application - Autoreload is disabled because the development mode is off.
2023-05-10 12:20:35.939 [main] INFO  ktor.application - Application started in 0.466 seconds.
2023-05-10 12:20:36.213 [DefaultDispatcher-worker-1] INFO  ktor.application - Responding at http://127.0.0.1:8080
2023-05-10 12:20:49.471 [eventLoopGroupProxy-4-1] TRACE io.ktor.routing.Routing - Trace for [ws]
/, segment:0 -> SUCCESS @ /
  /ws, segment:1 -> SUCCESS @ /ws
    /ws/(method:GET), segment:1 -> SUCCESS @ /ws/(method:GET)
      /ws/(method:GET)/(header:Connection = Upgrade), segment:1 -> SUCCESS @ /ws/(method:GET)/(header:Connection = Upgrade)
        /ws/(method:GET)/(header:Connection = Upgrade)/(header:Upgrade = websocket), segment:1 -> SUCCESS @ /ws/(method:GET)/(header:Connection = Upgrade)/(header:Upgrade = websocket)
  /, segment:0 -> SUCCESS @ /
    /(method:GET), segment:0 -> FAILURE "Not all segments matched" @ /(method:GET)
Matched routes:
  "" -> "ws" -> "(method:GET)" -> "(header:Connection = Upgrade)" -> "(header:Upgrade = websocket)"
Route resolve result:
  SUCCESS @ /ws/(method:GET)/(header:Connection = Upgrade)/(header:Upgrade = websocket)
2023-05-10 12:20:49.503 [eventLoopGroupProxy-3-5] TRACE io.ktor.websocket.WebSocket - Starting default WebSocketSession(io.ktor.websocket.DefaultWebSocketSessionImpl@6c7604ce) with negotiated extensions: 
2023-05-10 12:20:49.505 [eventLoopGroupProxy-3-6] TRACE io.ktor.websocket.WebSocket - Starting WebSocket pinger coroutine with period 15000 ms and timeout 15000 ms
2023-05-10 12:20:49.507 [eventLoopGroupProxy-3-5] TRACE io.ktor.server.websocket.WebSockets - Starting websocket session for /ws
2023-05-10 12:20:51.191 [eventLoopGroupProxy-3-1] TRACE io.ktor.websocket.WebSocket - WebSocketSession(StandaloneCoroutine{Active}@2199f12d) receiving frame Frame TEXT (fin=true, buffer len = 12)
2023-05-10 12:20:51.199 [eventLoopGroupProxy-3-2] TRACE io.ktor.websocket.WebSocket - Sending Frame TEXT (fin=true, buffer len = 22) from session io.ktor.websocket.DefaultWebSocketSessionImpl@6c7604ce
2023-05-10 12:20:56.097 [KtorShutdownHook] TRACE io.ktor.server.websocket.WebSockets - Shutdown WebSockets due to application stop
2023-05-10 12:20:56.098 [main] TRACE io.ktor.server.websocket.WebSockets - Shutdown WebSockets due to application stop
Exception in thread "DefaultDispatcher-worker-3" kotlinx.coroutines.CompletionHandlerException: Exception in completion handler ChildCompletion@69ad29cd[job@78879b92] for StandaloneCoroutine{Cancelled}@78879b92
	at kotlinx.coroutines.JobSupport.notifyCompletion(JobSupport.kt:1525)
	at kotlinx.coroutines.JobSupport.completeStateFinalization(JobSupport.kt:323)
	at kotlinx.coroutines.JobSupport.finalizeFinishingState(JobSupport.kt:240)
	at kotlinx.coroutines.JobSupport.tryMakeCompletingSlowPath(JobSupport.kt:906)
	at kotlinx.coroutines.JobSupport.tryMakeCompleting(JobSupport.kt:863)
	at kotlinx.coroutines.JobSupport.makeCompletingOnce$kotlinx_coroutines_core(JobSupport.kt:828)
	at kotlinx.coroutines.AbstractCoroutine.resumeWith(AbstractCoroutine.kt:100)
	at kotlin.coroutines.jvm.internal.BaseContinuationImpl.resumeWith(ContinuationImpl.kt:46)
	at kotlinx.coroutines.DispatchedTask.run(DispatchedTask.kt:233)
	at kotlinx.coroutines.internal.LimitedDispatcher.run(LimitedDispatcher.kt:42)
	at kotlinx.coroutines.scheduling.TaskImpl.run(Tasks.kt:95)
	at kotlinx.coroutines.scheduling.CoroutineScheduler.runSafely(CoroutineScheduler.kt:570)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.executeTask(CoroutineScheduler.kt:750)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.runWorker(CoroutineScheduler.kt:677)
	at kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.run(CoroutineScheduler.kt:664)
	Suppressed: kotlinx.coroutines.DiagnosticCoroutineContextException: [CoroutineName(raw-ws-handler), StandaloneCoroutine{Cancelled}@78879b92, io.ktor.server.netty.EventLoopGroupProxy@5b7e7fdd]
Caused by: kotlinx.coroutines.CompletionHandlerException: Exception in completion handler ResumeOnCompletion@29b1ec36[job@69cd7046] for JobImpl{Cancelled}@69cd7046
	at kotlinx.coroutines.JobSupport.notifyCompletion(JobSupport.kt:1525)
	at kotlinx.coroutines.JobSupport.completeStateFinalization(JobSupport.kt:323)
	at kotlinx.coroutines.JobSupport.finalizeFinishingState(JobSupport.kt:240)
	at kotlinx.coroutines.JobSupport.continueCompleting(JobSupport.kt:935)
	at kotlinx.coroutines.JobSupport.access$continueCompleting(JobSupport.kt:27)
	at kotlinx.coroutines.JobSupport$ChildCompletion.invoke(JobSupport.kt:1155)
	at kotlinx.coroutines.JobSupport.notifyCompletion(JobSupport.kt:1520)
	... 14 more
Caused by: java.util.concurrent.RejectedExecutionException: event executor terminated
	at io.netty.util.concurrent.SingleThreadEventExecutor.reject(SingleThreadEventExecutor.java:934)
	at io.netty.util.concurrent.SingleThreadEventExecutor.offerTask(SingleThreadEventExecutor.java:351)
	at io.netty.util.concurrent.SingleThreadEventExecutor.addTask(SingleThreadEventExecutor.java:344)
	at io.netty.util.concurrent.SingleThreadEventExecutor.execute(SingleThreadEventExecutor.java:836)
	at io.netty.util.concurrent.SingleThreadEventExecutor.execute0(SingleThreadEventExecutor.java:827)
	at io.netty.util.concurrent.SingleThreadEventExecutor.execute(SingleThreadEventExecutor.java:817)
	at io.ktor.server.netty.NettyDispatcher.dispatch(CIO.kt:68)
	at kotlinx.coroutines.DispatchedTaskKt.dispatch(DispatchedTask.kt:159)
	at kotlinx.coroutines.CancellableContinuationImpl.dispatchResume(CancellableContinuationImpl.kt:397)
	at kotlinx.coroutines.CancellableContinuationImpl.resumeImpl(CancellableContinuationImpl.kt:431)
	at kotlinx.coroutines.CancellableContinuationImpl.resumeImpl$default(CancellableContinuationImpl.kt:420)
	at kotlinx.coroutines.CancellableContinuationImpl.resumeWith(CancellableContinuationImpl.kt:328)
	at kotlinx.coroutines.ResumeOnCompletion.invoke(JobSupport.kt:1398)
	at kotlinx.coroutines.JobSupport.notifyCompletion(JobSupport.kt:1520)
	... 20 more

Process finished with exit code 1

```