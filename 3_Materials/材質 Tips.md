#基礎 #材質 
- Mapping::Vector -- Vector::Noise Texture::Color -- Vector::[[Voronoi Texture]] 可以產生不規則的曲線
- Texture Coordinate::Object -- Mapping::Vector
- 不用貼圖的水泥材質: https://www.youtube.com/watch?v=XDqRa0ExDqs
- 用 Noise 產生凹凸的連接法: 
  - Noise::Color -- Fac::ColorRamp::Color -- High::[[Bump]]::Normal -- Normal::[[BSDF]]
