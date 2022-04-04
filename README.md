# Switch-
include &lt;GUIConstants.au3> Global Const $DTM_SETFORMAT = 0x1005  $Form1 = GUICreate("Test", 300, 200) $dt_date1 = GUICtrlCreateDate("", 50, 50, 200, 21); implicitly long format $dt_date2 = GUICtrlCreateDate("", 50, 100, 200, 21, $DTS_SHORTDATEFORMAT) GUISetState(@SW_SHOW)  While 1     Switch GuiGetMsg()         Case $GUI_EVENT_CLOSE             Exit     EndSwitch WEnd
