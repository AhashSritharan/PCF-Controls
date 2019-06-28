# PCF-Controls
Controls using PowerApps Components Framework

## NN Checkboxes

[Download](https://github.com/MscrmTools/PCF-Controls/releases/)

### Purpose
The purpose of this control is to allow user to associate/disassociate records for a many-to-many relationship displaying all possible records as checkboxes or toggle switches

![Vidéo](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/video.gif?raw=true)

New in version 1.1
- You can choose the number of columns to render
- Relationship schema name is not mandatory if only one many-to-many relationship exists for the entities
- Records can be rendered with background color and forecolor if the entity has corresponding attributes
- Records can be grouped by an attribute (text, optionset or booleans)

![Update1.1](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/ColorAndGroups.png?raw=true)

### Configuration

This is the list of parameters that can be set on the control

|Parameter|Description|Required|Bound to an attribute|
|---------|-----------|:----:|:---:|
|**Display attribute**|Attribute to use as label for the checkbox|X|X|
|**Relationship schema name**|Schema name of the relationship. *required only if multiple many-to-many relationship exist for both related entities*|?||
|**Parent entity logical name**|Logical name of the current form entity|X||
|**Background color**|Attribute to use as background color||X|
|**Color**|Attribute to use as forecolor||X|
|**Columns**|Number of columns to display checkboxes|X||
|**Grouping Attribute**|Attribute used to group records. *If used, this attribute must be the first attribute used to sort the view used by this control*|X|
|**Use Toggle switch**|"true" if you want to display toggle switch instead of checkboxes|||
|**Switch Off color**|Default background color when the switch is Off. *This parameter is overriden by the parameter **Background color***||X|
|**Switch On color**|Default background color when the switch is On. *This parameter is overriden by the parameter **Background color***||X|



