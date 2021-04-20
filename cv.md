# *CV*

# Ivan Budovich

## Contact Info 
* *e-mail:* ibudovichivan3@gmail.com
* *Telegram:* @nikolssen
* *Cell phone:* +375 44 788 02 01
## Summary
Hail! My name is Ivan, I'm a BSUIR student. I aspire to become IOS 
developer. I speak Russian and Belarusian as well as I am fluent in English and Polish.
## Skills
* C/Objective-C langauage
* Swift language
* PHP basics
* UIKit
* Knowlegde of OOP
## Experience
Unfortunately, no
## Education
* Belarusian State University Lyceum (2017-2019)
* Belarusian State University of Informatics and Radioelectronics (2019- )
* Swift Training from HSE Moscow (2019, in BSUIR)
* RS School iOS 2020 (First Stage Nominee)
## Code examples
``` Swift 
func draw(isPrototype: Bool) {
        if points.count > 1
        {
            
            let polygonPath = UIBezierPath()
            polygonPath.move(to: points.first!)
            for point in points[1...] {
                polygonPath.addLine(to: point)
            }
            if points.count == 4{
                polygonPath.close()
                fill.color.setFill()
                polygonPath.fill(with: .normal, alpha: fill.opacity)
            }
            
            polygonPath.lineWidth = CGFloat(stroke.width)
            
            stroke.color.setStroke()
            if isPrototype
            {
                let dash = [CGFloat(15.0), CGFloat(15.0)]
                polygonPath.setLineDash(dash, count: 2, phase: CGFloat(30))
            }
            polygonPath.stroke()
            
        }
    }
```
## English
* Due to EPAM test - B2+
