lib_LTLIBRARIES = libtemplate.la

AM_CPPFLAGS = -I@top_srcdir@/include -I. $(LTDLINCL)

libtemplate_la_LDFLAGS = -no-undefined  -version-info 1:0:0 

EXTRA_DIST = \
	driver.h \
	prototypes.h \
	driverextras.h 

libtemplate_la_LIBADD = \
	../../lst/liblstlc.la \
	../../log/libloglc.la \
	../../ini/libinilc.la \
	../../odbcinst/libodbcinstlc.la \
	$(LIBLTDL) 

libtemplate_la_SOURCES = \
	SQLAllocConnect.c \
	SQLAllocEnv.c \
	SQLAllocHandle.c \
	SQLAllocStmt.c \
	SQLBindCol.c \
	SQLBindParameter.c \
	SQLBrowseConnect.c \
	SQLBulkOperations.c \
	SQLCancel.c \
	SQLCloseCursor.c \
	SQLColAttribute.c \
	SQLColAttributes.c \
	SQLColumnPrivileges.c \
	SQLColumns.c \
	SQLConnect.c \
	SQLCopyDesc.c \
	SQLDescribeCol.c \
	SQLDescribeParam.c \
	SQLDisconnect.c \
	SQLDriverConnect.c \
	SQLEndTran.c \
	SQLError.c \
	SQLExecDirect.c \
	SQLExecute.c \
	SQLExtendedFetch.c \
	SQLFetch.c \
	SQLFetchScroll.c \
	SQLForeignKeys.c \
	SQLFreeConnect.c \
	SQLFreeEnv.c \
	SQLFreeHandle.c \
	SQLFreeStmt.c \
	SQLGetConnectAttr.c \
	SQLGetConnectOption.c \
	SQLGetCursorName.c \
	SQLGetData.c \
	SQLGetDescField.c \
	SQLGetDescRec.c \
	SQLGetDiagField.c \
	SQLGetDiagRec.c \
	SQLGetEnvAttr.c \
	SQLGetInfo.c \
	SQLGetStmtAttr.c \
	SQLGetStmtOption.c \
	SQLGetTypeInfo.c \
	SQLMoreResults.c \
	SQLNativeSql.c \
	SQLNumParams.c \
	SQLNumResultCols.c \
	SQLParamData.c \
	SQLParamOptions.c \
	SQLPrepare.c \
	SQLPrimaryKeys.c \
	SQLProcedureColumns.c \
	SQLProcedures.c \
	SQLPutData.c \
	SQLRowCount.c \
	SQLSetConnectOption.c \
	SQLSetCursorName.c \
	SQLSetDescField.c \
	SQLSetDescRec.c \
	SQLSetEnvAttr.c \
	SQLSetParam.c \
	SQLSetPos.c \
	SQLSetScrollOptions.c \
	SQLSetStmtAttr.c \
	SQLSetStmtOption.c \
	SQLSpecialColumns.c \
	SQLStatistics.c \
	SQLTablePrivileges.c \
	SQLTables.c \
	SQLTransact.c \
	_FreeDbc.c \
	_FreeStmt.c \
	_FreeDbcList.c \
	_FreeStmtList.c \
	_FreeResults.c \
	_GetData.c \
	_NativeToSQLColumnHeader.c \
	_NativeToSQLType.c \
	_NativeTypeDesc.c \
	_NativeTypeLength.c \
	_NativeTypePrecision.c
