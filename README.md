## Components in used

**Cube**

Property | Description | Type | Default
--- | --- | --- | ---
**nid** | The id for cube | any | -
**data** | Clip card data | any | -
**z** | Set zIndex for cube | string | -
**videoId** | The id for video | string | -
**phase** | Set phase for cube | ```creating | minting | final | preview | detail | medium | outline``` | -
**width** | Width for cube | string | -
**height** | Height for cube | string | -
**autoPlay** | Determines whether the video starts automatically or not | boolean | -
**autoRotate** | Auto rotate when start or not? | boolean | -
**allowPlayer** | Allow can play video | boolean | -
**isEdition** | Set true if is Edition Clip Card | boolean | -

------

**ClipFace**

Property | Description | Type | Default
--- | --- | --- | ---
**data** | Clip card data | any | -
**layoutStyleCls** | Edition layout name | string | -
**onImageClick** | Callback when click image | () => void | -
**isEdition** | Set true if is Edition Clip Card | boolean | -

------

**DescriptionFace**,  **ProvenanceFace**,  **VideoInfoFace**

Property | Description | Type | Default
--- | --- | --- | ---
**data** | Clip card data | any | -

------

**VideoFace**

Property | Description | Type | Default
--- | --- | --- | ---
**data** | Clip card data | any | -
**videoId** | The id for video | string | -
**phase** | Set phase for cube | `creating | minting | final | preview | detail | medium | outline` | -
**onVideoClick** | Callback when click video | boolean | -
**autoPlay** | Determines whether the video starts automatically or not | () => void | -
