1: baked light is static on the object
2: Mixed light can be baked and used as realtime
3: once a object is static, it always be baked.
4: both realtime GI and baked GI must use static object for light bounces
5: mixed light will bake light first, then a realtime light is generated.
6: Direct Sample and Indirect Sample are how far ray are used to generate light.
7: mixed light has spot
8: Distance Shadowmask is used to generate high quality shadow in short distance but low quality in long distance.
9: Shadowmask and indirectmap have same quality, subatractive has bad quality but efficient.