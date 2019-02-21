ember-leaflet-fullscreen-control
==============================================================================

Use [leaflet.fullscreen](https://github.com/brunob/leaflet.fullscreen) in Ember with [ember-leaflet](https://ember-leaflet.com).



Installation
------------------------------------------------------------------------------

```
ember install ember-leaflet-fullscreen-control
```


Usage
------------------------------------------------------------------------------

```hbs
<LeafletMap …>
  {{!-- … --}}
  <LeafletFullscreenControl />
</LeafletMap>
```

All leaflet.fullscreen are support like this `<LeafletFullscreenControl @position="topleft" />`. Have a look at the leaflet.fullscreen readme. The enter/exit fullscreen events are not supported, yet.

License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
