## Components in used

**Cube**

Property | Description | Type | Default
--- | --- | --- | ---
**nid** | The id for cube | any | -
**data** | Clip card data | any | -
**z** | Set zIndex for cube | string | -1000
**videoId** | The id for video | string | -
**phase** | Set phase for cube | string | creating
**width** | Width for cube | string | 50vmin
**height** | Height for cube | string | 50vmin
**autoPlay** | Determines whether the video starts automatically or not | boolean | false
**autoRotate** | Auto rotate when start or not? | boolean | false
**allowPlayer** | Allow can play video | boolean | false
**isEdition** | Set true if is Edition Clip Card | boolean | false

```Phase: creating | minting | final | preview | detail | medium | outline```

------

**ClipFace**

Property | Description | Type | Default
--- | --- | --- | ---
**data** | Clip card data | any | -
**layoutStyleCls** | Edition layout name | string | -
**onImageClick** | Callback when click image | () => void | -
**isEdition** | Set true if is Edition Clip Card | boolean | false


------

**VideoFace**

Property | Description | Type | Default
--- | --- | --- | ---
**data** | Clip card data | any | -
**videoId** | The id for video | string | -
**phase** | Set phase for cube | string | -
**onVideoClick** | Callback when click video | boolean | -
**autoPlay** | Determines whether the video starts automatically or not | () => void | false

```Phase: creating | minting | final | preview | detail | medium | outline```

------

**DescriptionFace** | **ProvenanceFace** | **VideoInfoFace**

Property | Description | Type | Default
--- | --- | --- | ---
**data** | Clip card data | any | -
