
# Leaflet.draw-ellipse
Adds support for drawing and editing ellipses in the [Leaflet.draw](https://github.com/Leaflet/Leaflet.draw) plugin. Check out the [demo](http://haleystorm.github.io/Leaflet.draw-ellipse/).

# Important
Leaflet.draw-ellipse 0.1.0+ requires 

+ [Leaflet 0.7](https://github.com/Leaflet/Leaflet/releases/tag/v0.7) or [Leaflet 1.7.1](https://github.com/Leaflet/Leaflet/releases/tag/v1.7.1)
+ [Leaflet.draw 1.0.4](https://github.com/Leaflet/Leaflet.draw/releases/tag/v1.0.4)
+ [Leaflet.ellipse](https://github.com/jdfergason/Leaflet.Ellipse)

## Usage

See [Leaflet.draw](https://github.com/Leaflet/Leaflet.draw#using) and [Leaflet.ellipse](https://github.com/jdfergason/Leaflet.Ellipse#usage).

## Options

You can configure the Leaflet.draw control by using the following options. They are the same as [CircleOptions](https://leaflet.github.io/Leaflet.draw/docs/leaflet-draw-latest.html#circleoptions).

### EllipseOptions

| Option | Type | Default | Description
| --- | --- | --- | ---
| shapeOptions | [Leaflet Path options](https://leafletjs.com/reference-1.7.1.html#path) | [See code](https://github.com/Leaflet/Leaflet.draw/blob/master/src/draw/handler/Draw.Circle.js#L7) | The options used when drawing the ellipse on the map. 
| repeatMode | Bool | `false` | Determines if the draw tool remains enabled after drawing a shape.
