## API

| Property | Description | Type | Default |
| -------- | ----------- | ---- | ------- |
| --- | --- | --- | --- |
| closable | Whether a close (x) button is visible on top right of the Drawer dialog or not. | boolean | true |
| destroyOnClose | Whether to unmount child components on closing drawer or not. | boolean | false |
| getContainer | Return the mounted node for Drawer. | HTMLElement \| `() => HTMLElement` \| selectors   | 'body' |
| mask | Whether to show mask or not. | Boolean | true |
| maskClosable | Clicking on the mask (area outside the Drawer) to close the Drawer or not. | boolean | true |
| maskStyle | Style for Drawer's mask element. | object | {} |
| title | The title for Drawer. | string\|slot | - |
| visible | Whether the Drawer dialog is visible or not. | boolean | false |
| wrapClassName | The class name of the container of the Drawer dialog. | string | - |
| width | Width of the Drawer dialog. | string\|number | 256 |
| height | placement is `top` or `bottom`, height of the Drawer dialog. | string\|number | - |
| className | The class name of the container of the Drawer dialog. | string | - |
| zIndex | The `z-index` of the Drawer. | Number | 1000 |
| placement | The placement of the Drawer. | 'top'  \| 'right' \| 'bottom' \| 'left' | 'right' |


## Methods

| Name | Description | Type | Default |
| ---- | ----------- | ---- | ------- |
| close | Specify a callback that will be called when a user clicks mask, close button or Cancel button. | function(e) | - |
