---
sidebar_position: 60 
---

# ListBox

### At a Glance

|Parent Class| Interfaces |
|------------|------------|
|[AbstractDwclistControl](#)| <ul><li>[HasScroll](#)</li><li>[HasReadOnly](#)</li><li>[HasMouseWheelCondition](#)</li><li>[HasFocus](#)</li><li>[HasTabTraversal](#)</li><li>[HasTextAlignment](#)</li></ul>|

| Methods |
|------------|
| <ul><li>[`ListBox addItem(Object key, String item)`](#)</li><li>[`ListBox addItems(Map<Object, String> items)`](#)</li><li>[`ListBox deselectAll()`](#)</li><li>[`ListBox deselectIndex(int index)`](#)</li><li>[`Map<Object, String> getAllItems()`](#)</li><li>[`SimpleEntry<Object, String> getEntryByValue(String value)`](#)</li><li>[`String getItem(Object key)`](#)</li><li>[`String getItemAt(Integer idx)`](#)</li><li>[`SimpleEntry<Object, String> getSelectedItem()`](#)</li><li>[`Map<Object, String> getSelectedItems()`](#)</li><li>[`Boolean isMultipleSelection()`](#)</li><li>[`ListBox insertItemAt(Object key, String item, Integer index)`](#)</li><li>[`ListBox insertItemsAt(Map<Object, String> items, Integer index)`](#)</li><li>[`ListBox removeAllItems()`](#)</li><li>[`ListBox removeItemAt(Integer idx)`](#)</li><li>[`ListBox selectIndex(Integer idx)`](#)</li><li>[`ListBox setExpanse(Expanse expanse)`](#)</li><li>[`ListBox setItems(Map<Object, String> values)`](#)</li><li>[`ListBox setMultipleSelection(Boolean multipleSelection)`](#)</li><li>[`ListBox setTextAt(Integer idx, String text)`](#)</li></ul>|


| Events |
|------------|
| <ul><li>[`ListBox onSelect(Consumer<ListBoxSelectEvent> callback)`](#)</li><li>[`ListBox onDoubleClick(Consumer<ListBoxDoubleClickEvent> callback)`](#)</li></ul> |

### Multiple Selection

### Label

### Expanses