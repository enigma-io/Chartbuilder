Chartbuilder / Gneisschart
==========================

This is Enigma's customized deploy of [Quartz Chartbuilder / Gneisschart](https://github.com/Quartz/Chartbuilder).

You can view it [here](http://chartbuilder.enigmalabs.org/).

## How do I customize the chart?

Chart configuration is handled by passing a configuration object through to `ChartBuilder.start()`.

    ChartBuilder.start({
      colors: ["#ff4cf4","#ffb3ff","#e69ce6","#cc87cc","#b373b3","#995f99"],
      creditline: 'NewsPost Inc.'
    });

## How do I customize the styles?

Chart styles are contained in `css/gneisschart.css`. The color palette is defined in the configuration object

## TODO:

- [ ] Add in Enigma Colors
- [ ] Add Enigma Logo to Chart. 

