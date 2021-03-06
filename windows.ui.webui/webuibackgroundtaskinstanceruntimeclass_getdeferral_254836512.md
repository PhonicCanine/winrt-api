---
-api-id: M:Windows.UI.WebUI.WebUIBackgroundTaskInstanceRuntimeClass.GetDeferral
-api-type: winrt method
---

<!-- Method syntax
public Windows.ApplicationModel.Background.BackgroundTaskDeferral GetDeferral()
-->

# Windows.UI.WebUI.WebUIBackgroundTaskInstanceRuntimeClass.GetDeferral

## -description
Informs the system that the background task might continue to perform work after the [IBackgroundTask.Run](../windows.applicationmodel.background/ibackgroundtask_run.md) method returns. This method is not applicable to JavaScript background tasks.

## -returns
A background task deferral.

## -remarks
This method is not applicable for background tasks written in JavaScript. JavaScript background tasks use the Web Workers [close](http://go.microsoft.com/fwlink/p/?linkid=237467) method to finish the task after all asynchronous operations have completed.

## -examples

## -see-also
