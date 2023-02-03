---
sidebar_position: 110
---

# Slider

### At a Glance

|Parent Class| Interfaces |
|------------|------------|
|[AbstractDwcControl](#)| <ul><li>[HasMouseWheelCondition](#)</li><li>[HasFocus](#)</li><li>[HasTabTraversal](#)</li></ul>|

| Methods |
|------------|
| <ul><li>[`Map<Integer,String> getLabels()`](#)</li><li>[`Integer getMajorTickSpacing()`](#)</li><li>[`Integer getMaximum()`](#)</li><li>[`Integer getMinimum()`](#)</li><li>[`Integer getMinorTickSpacing()`](#)</li><li>[`Integer getOrientation()`](#)</li><li>[`Integer getValue()`](#)</li><li>[`Boolean isInverted()`](#)</li><li>[`Boolean isPaintLabels()`](#)</li><li>[`Boolean isPaintTicks()`](#)</li><li>[`Boolean isSnapToTicks()`](#)</li><li>[`Slider setInverted(Boolean inverted)`](#)</li><li>[`Slider setLabels(Map<Integer,String> labels)`](#)</li><li>[`Slider setMajorTickSpacing(Integer tick)`](#)</li><li>[`Slider setMaximum(Integer maximum)`](#)</li><li>[`Slider setMinimum(Integer minimum)`](#)</li><li>[`Slider setMinorTickSpacing(Integer tick)`](#)</li><li>[`Slider setOrientation(Orientation orientation)`](#)</li><li>[`Slider setPaintLabels(Boolean paint)`](#)</li><li>[`Slider setPaintTicks(Boolean paint)`](#)</li><li>[`Slider setSnapToTicks(Boolean snap)`](#)</li><li>[`Slider setValue(Integer value)`](#)</li></ul>|


| Events |
|------------|
| <ul><li>[`Slider onScroll(Consumer<SliderOnControlScrollEvent> callback)`](#)</li></ul> |


### Major and Minor Ticks

Slider controls can be customized to show ticks, or spaces bounded by lines to represent distances. Major ticks will be larger and more noticeable than minor ticks, and both can be configured to appear at the desired intervals. 

### Upper and Lower Limit


### Orientation and Inversion


### Theme