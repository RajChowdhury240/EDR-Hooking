# EDR-Hooking

| EDR/API                                  | attivo | sentinelone | cortex | sophos | mcafee | crowdstrike | morphisec | cylance | deepinstinct | carbonblack | symantec |
|------------------------------------------|--------|-------------|--------|--------|--------|-------------|-----------|---------|--------------|-------------|----------|
| KiUserApcDispatcher                      | FALSE  | TRUE        | FALSE  | TRUE   | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| KiUserExceptionDispatcher                | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| LdrFindEntryForAddress                   | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| LdrLoadDll                               | FALSE  | TRUE        | FALSE  | TRUE   | TRUE   | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| LdrOpenImageFileOptionsKey               | TRUE   | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| LdrResolveDelayLoadedAPI                 | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| NtAddBootEntry                           | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtAdjustPrivilegesToken                  | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtAlertResumeThread                      | FALSE  | FALSE       | FALSE  | FALSE  | TRUE   | FALSE       | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| NtAllocateVirtualMemory                  | FALSE  | TRUE        | TRUE   | TRUE   | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| NtAllocateVirtualMemoryEx                | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtAlpcConnectPort                        | FALSE  | FALSE       | FALSE  | TRUE   | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtAreMappedFilesTheSame                  | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| NtClose                                  | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | TRUE         | TRUE        | FALSE    |
| NtCreateFile                             | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | TRUE     |
| NtCreateKey                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtCreateMutant                           | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtCreateProcess                          | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | TRUE    | TRUE         | FALSE       | FALSE    |
| NtCreateProcessEx                        | TRUE   | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | TRUE    | TRUE         | FALSE       | FALSE    |
| NtCreateSection                          | TRUE   | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| NtCreateThread                           | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| NtCreateThreadEx                         | FALSE  | TRUE        | FALSE  | FALSE  | TRUE   | FALSE       | FALSE     | TRUE    | TRUE         | TRUE        | FALSE    |
| NtCreateUserProcess                      | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | TRUE    | FALSE        | FALSE       | TRUE     |
| NtDelayExecution                         | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtDeleteBootEntry                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtDeleteFile                             | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtDeleteKey                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtDeleteValueKey                         | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtDeviceIoControlFile                    | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtDuplicateObject                        | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| NtFreeVirtualMemory                      | FALSE  | TRUE        | FALSE  | TRUE   | FALSE  | FALSE       | FALSE     | TRUE    | FALSE        | FALSE       | FALSE    |
| NtGdiBitBlt                              | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtGetContextThread                       | FALSE  | FALSE       | FALSE  | FALSE  | TRUE   | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtLoadDriver                             | FALSE  | TRUE        | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtMapUserPhysicalPages                   | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtMapViewOfSection                       | FALSE  | TRUE        | TRUE   | TRUE   | TRUE   | TRUE        | TRUE      | TRUE    | TRUE         | TRUE        | TRUE     |
| NtMapViewOfSectionEx                     | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtModifyBootEntry                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtOpenCreateFile                         | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtOpenFile                               | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtOpenKey                                | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtOpenKeyEx                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtOpenProcess                            | TRUE   | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| NtOpenProcessToken                       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtOpenProcessTokenEx                     | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtOpenThreadToken                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtOpenThreadTokenEx                      | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtProtectVirtualMemory                   | TRUE   | TRUE        | TRUE   | TRUE   | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| NtQueryAttributesFile                    | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| NtQueryFullAttributesFile                | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| NtQueryInformationProcess                | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| NtQueryInformationThread                 | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtQueryInformationTokenTokenUser         | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtQuerySystemInformation                 | FALSE  | TRUE        | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| NtQuerySystemInformationEx               | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtQueryVirtualMemory                     | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| NtQueueApcThread                         | FALSE  | TRUE        | TRUE   | TRUE   | TRUE   | TRUE        | TRUE      | TRUE    | TRUE         | TRUE        | FALSE    |
| NtQueueApcThreadEx                       | FALSE  | TRUE        | TRUE   | FALSE  | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| NtQueueApcThreadEx2                      | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtReadVirtualMemory                      | TRUE   | TRUE        | TRUE   | TRUE   | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| NtRenameKey                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtResumeThread                           | FALSE  | TRUE        | FALSE  | FALSE  | TRUE   | TRUE        | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| NtSetContextThread                       | FALSE  | TRUE        | TRUE   | TRUE   | TRUE   | TRUE        | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| NtSetInformationFile                     | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtSetInformationProcess                  | FALSE  | TRUE        | TRUE   | FALSE  | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | FALSE       | FALSE    |
| NtSetInformationProcessCriticalProcess   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtSetInformationThread                   | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtSetInformationThreadCriticalThread     | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtSetInformationThreadHideFromDebugger   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtSetInformationThreadImpersonationToken | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtSetInformationThreadWow64Context       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtSetInformationVirtualMemory            | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtSetValueKey                            | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtSuspendThread                          | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtSystemDebugControl                     | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtTerminateProcess                       | TRUE   | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtTerminateThread                        | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| NtUnmapViewOfSection                     | FALSE  | TRUE        | TRUE   | TRUE   | TRUE   | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| NtUnmapViewOfSectionEx                   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtUserGetAsyncKeyState                   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtUserGetClipboardData                   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtUserSetWindowsHookEx                   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| NtWriteFile                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| NtWriteVirtualMemory                     | TRUE   | TRUE        | TRUE   | TRUE   | TRUE   | TRUE        | FALSE     | TRUE    | TRUE         | TRUE        | FALSE    |
| RegNtCallbackObjectContextCleanup        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostCreateKey                       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostCreateKeyEx                     | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostDeleteKey                       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostDeleteValueKey                  | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostEnumerateKey                    | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostEnumerateValueKey               | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostFlushKey                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostKeyHandleClose                  | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostLoadKey                         | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostOpenKey                         | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostOpenKeyEx                       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostQueryKey                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostQueryKeyName                    | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostQueryKeySecurity                | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostQueryMultipleValueKey           | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostQueryValueKey                   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostRenameKey                       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostReplaceKey                      | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostRestoreKey                      | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostSaveKey                         | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostSetInformationKey               | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostSetKeySecurity                  | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostSetValueKey                     | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPostUnLoadKey                       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreCreateKey                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreCreateKeyEx                      | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreDeleteKey                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreDeleteValueKey                   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreEnumerateKey                     | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreEnumerateValueKey                | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreFlushKey                         | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreKeyHandleClose                   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreLoadKey                          | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreOpenKey                          | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreOpenKeyEx                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreQueryKey                         | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreQueryKeyName                     | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreQueryKeySecurity                 | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreQueryMultipleValueKey            | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreQueryValueKey                    | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreRenameKey                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreReplaceKey                       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreRestoreKey                       | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreSaveKey                          | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreSetInformationKey                | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreSetKeySecurity                   | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreSetValueKey                      | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RegNtPreUnLoadKey                        | FALSE  | FALSE       | TRUE   | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RtlAddVectoredExceptionHandler           | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RtlCreateUserThread                      | FALSE  | FALSE       | FALSE  | FALSE  | TRUE   | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| RtlDosApplyFileIsolationRedirection_Ustr | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| RtlGetNativeSystemInformation            | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| RtlInstallFunctionTableCallback          | FALSE  | FALSE       | FALSE  | TRUE   | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwAlertResumeThread                      | FALSE  | FALSE       | FALSE  | FALSE  | TRUE   | FALSE       | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| ZwAllocateVirtualMemory                  | FALSE  | TRUE        | FALSE  | TRUE   | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| ZwAllocateVirtualMemoryEx                | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwAlpcConnectPort                        | FALSE  | FALSE       | FALSE  | TRUE   | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwAreMappedFilesTheSame                  | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwClose                                  | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | TRUE         | TRUE        | FALSE    |
| ZwCreateFile                             | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | TRUE     |
| ZwCreateKey                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwCreateProcess                          | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | TRUE    | TRUE         | FALSE       | FALSE    |
| ZwCreateProcessEx                        | TRUE   | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | TRUE    | TRUE         | FALSE       | FALSE    |
| ZwCreateSection                          | TRUE   | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| ZwCreateThread                           | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| ZwCreateThreadEx                         | FALSE  | TRUE        | FALSE  | FALSE  | TRUE   | FALSE       | FALSE     | TRUE    | TRUE         | TRUE        | FALSE    |
| ZwCreateUserProcess                      | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | TRUE    | FALSE        | FALSE       | TRUE     |
| ZwDeleteFile                             | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwDeleteKey                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwDeleteValueKey                         | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwDeviceIoControlFile                    | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwDuplicateObject                        | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| ZwFreeVirtualMemory                      | FALSE  | TRUE        | FALSE  | TRUE   | FALSE  | FALSE       | FALSE     | TRUE    | FALSE        | FALSE       | FALSE    |
| ZwGetContextThread                       | FALSE  | FALSE       | FALSE  | FALSE  | TRUE   | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwLoadDriver                             | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwMapUserPhysicalPages                   | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwMapViewOfSection                       | FALSE  | TRUE        | FALSE  | TRUE   | TRUE   | TRUE        | TRUE      | TRUE    | TRUE         | TRUE        | TRUE     |
| ZwMapViewOfSectionEx                     | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwOpenFile                               | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwOpenKey                                | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwOpenKeyEx                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwOpenProcess                            | TRUE   | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| ZwProtectVirtualMemory                   | TRUE   | TRUE        | FALSE  | TRUE   | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| ZwQueryAttributesFile                    | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwQueryFullAttributesFile                | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwQueryInformationProcess                | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| ZwQueryInformationThread                 | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwQuerySystemInformation                 | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| ZwQuerySystemInformationEx               | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwQueryVirtualMemory                     | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | TRUE      | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwQueueApcThread                         | FALSE  | TRUE        | FALSE  | TRUE   | TRUE   | TRUE        | TRUE      | TRUE    | TRUE         | TRUE        | FALSE    |
| ZwQueueApcThreadEx                       | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| ZwReadVirtualMemory                      | TRUE   | TRUE        | FALSE  | TRUE   | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| ZwRenameKey                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwResumeThread                           | FALSE  | TRUE        | FALSE  | FALSE  | TRUE   | TRUE        | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| ZwSetContextThread                       | FALSE  | TRUE        | FALSE  | TRUE   | TRUE   | TRUE        | FALSE     | FALSE   | TRUE         | FALSE       | FALSE    |
| ZwSetInformationFile                     | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwSetInformationProcess                  | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | TRUE    | FALSE        | FALSE       | FALSE    |
| ZwSetInformationThread                   | FALSE  | TRUE        | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwSetValueKey                            | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwSuspendThread                          | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwTerminateProcess                       | TRUE   | TRUE        | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwTerminateThread                        | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | FALSE       | TRUE     |
| ZwUnmapViewOfSection                     | FALSE  | TRUE        | FALSE  | TRUE   | TRUE   | TRUE        | FALSE     | TRUE    | FALSE        | TRUE        | FALSE    |
| ZwUnmapViewOfSectionEx                   | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | TRUE        | FALSE     | FALSE   | FALSE        | FALSE       | FALSE    |
| ZwWriteFile                              | FALSE  | FALSE       | FALSE  | FALSE  | FALSE  | FALSE       | FALSE     | FALSE   | FALSE        | TRUE        | FALSE    |
| ZwWriteVirtualMemory                     | TRUE   | TRUE        | FALSE  | TRUE   | TRUE   | TRUE        | FALSE     | TRUE    | TRUE         | TRUE        | FALSE    |

# EDRs Hooked APIs


### CrowdStrike hooked ntdll.dll APIs

[CrowdStrike hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/crowdstrike.txt)

The newer version moved away from UMH and instead rely on kernel callback as shown below:

![kernel callback](https://github.com/Mr-Un1k0d3r/EDRs/raw/main/kernel-callback.png)


### SentinelOne hooked ntdll.dll APIs

[SentinelOne hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/sentinelone.txt)

### Cylance hooked ntdll.dll APIs (Thanks to Seemant Bisht)

[Cylance hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/cylance.txt)

### Sophos hooked ntdll.dll APIs

[Sophos hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/sophos.txt)

### Attivo Deception hooked ntdll.dll APIs

[Attivo hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/attivo.txt)

### CarbonBlack hooked ntdll.dll APIs (Thanks to Hackndo)

[CarbonBlack hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/carbonblack.txt)

### Symantec hooked ntdll.dll APIs (Thanks to CarsonSallis)

[Symantec hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/symantec.txt)

### DeepInstinct hooked ntdll.dll APIs (Thanks to P0chAcc0)

[DeepInstinct hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/deepinstinct.txt)

### McAfee hooked ntdll.dll APIs

[McAfee hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/mcafee.txt)

## CheckPoint SandBlast hooked ntdll APIs

[CheckPoint SandBlast hooks list](https://github.com/Mr-Un1k0d3r/EDRs/blob/main/checkpoint-sandblast.txt)

## ESET endpoint Security 8.0.2028.0 hooked ntdll APIs

[Eset hooks list](https://github.com/Mr-Un1k0d3r/EDRs/blob/main/eset.txt)

## TrendMicro 17.7.1130 hooked ntdll APIs

[TrendMicro hooks list](https://github.com/Mr-Un1k0d3r/EDRs/blob/main/trend.txt)

### Cortex XDR hooked APIs (KERNEL MODE)

:warning: These hooks are set kernel mode. They can't be unhooked from the user mode

[Cortex XDR hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/cortex.txt)

## Bitdefender hooked ntdll APIs

[Bitdefender hooks list](https://github.com/Mr-Un1k0d3r/EDRs/blob/main/bitdefender.txt)
