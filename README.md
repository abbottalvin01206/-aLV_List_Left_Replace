# -aLV_List_Left_Replace
_GUIListViewEx_Delete() Case $cReset_Button ; Note parameter required for each step ; Remove current ListView from UDF _GUIListViewEx_Close($iLV_Left_Index) ; UDF index ; Delete all items _GUICtrlListView_DeleteAllItems($cListView_Left) ; ControlID/handle ; Refill the ListView with new data For $i = 1 To UBound($aLV_List_Left_Replace) - 1 GUICtrlCreateListViewItem($aLV_List_Left_Replace[$i], $cListView_Left) ; ControlID/handle ; Re-initiate ListView
