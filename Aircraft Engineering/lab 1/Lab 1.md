# Lab 1: wing geometry and the aircraft mission profile

Student name: Zhichao Wang

Student email: hansen_wong@sjtu.edu.cn

[toc]

## 1. Aircraft Choice

I chose Lockheed Model 10 Electra. The Lockheed Model 10 Electra is an American twin-engined, all-metal monoplane airliner developed by the Lockheed Aircraft Corporation in the 1930s to compete with the Boeing 247 and Douglas DC-2. The type gained considerable fame as one was flown by Amelia Earhart on her ill-fated around-the-world expedition in 1937. The aircraft is shown in the figure below.

![Lockheed Model 10 Electra](https://upload.wikimedia.org/wikipedia/commons/3/36/Earhart-electra_10.jpg)

## 2. Mission Profile

The Lockheed Model 10 Electra was designed as **a commercial airliner for medium-range flights**, capable of carrying up to ten passengers and two pilots. Its mission profile included **passenger transport**, **air mail delivery**, and **executive transportation**. The aircraft's reliability also made it well-suited for use in **exploration and survey missions**, such as those conducted by Amelia Earhart during her ill-fated circumnavigation attempt in 1937.

During World War II, the Lockheed Model 10 Electra was used by various military forces for transport, reconnaissance, and training purposes. Some models were modified with additional fuel tanks, upgraded engines, and defensive armaments, enabling them to fly longer distances and at higher altitudes.

A few Lockheed Model 10 Electra remain operational today, primarily in private or museum collections. They are highly prized for their historical significance and unique design and continue to inspire aviation enthusiasts and historians alike.

Some specifications about the aircraft are listed below. [^1]

[^1]: https://www.wikiwand.com/en/Lockheed_Model_10_Electra#Specifications_(Electra_10A)

| Parameter | Value                                         |
| ------------ | ------------------------------------------------ |
| Crew | 2 |
| Capacity | 10 passengers + 670 lb (304 kg) mail and baggage |
| Length | 38 ft 7 in (11.76 m) |
| Wingspan | 55 ft (17 m) |
| Wing area | 458.3 sq ft (42.58 m2) |
| Height | 10 ft 1 in (3.07 m) |
| Fuel Capacity | 194 US gal (161.5 imp gal; 734.4 l) in center-section leading edges and fuselage |
| Powerplant | 2 × Pratt & Whitney R-985 Wasp Junior SB 9-cylinder air-cooled radial piston engines, 450 hp (340 kW) each at 2,300 rpm at 5,000 ft (1,524 m) |
| Range | 810 mi (1,300 km, 700 nmi) at 75% power with maximum fuel |
| Maximum speed | 190 mph (310 km/h, 170 kn) at sea level, fully loaded<br />210 mph (182 kn; 338 km/h) at 5,000 ft (1,524 m) |
| Cruise speed | 176 mph (283 km/h, 153 kn) at sea level<br />185 mph (161 kn; 298 km/h) at 5,000 ft (1,524 m)<br />195 mph (169 kn; 314 km/h) at 9,600 ft (2,926 m) |

## 3. Discuss the wing geometry

###  Description

| Wing geometry feature                                | Flight performance/mission profile                           | How it works                                                 |
| ---------------------------------------------------- | :----------------------------------------------------------- | ------------------------------------------------------------ |
| Proper Aspect Ratio                                  | Generate enough lift<br />Better fuel efficiency and range<br />Improve stability | An AR of 7.2 is not a large one today, but it was a rather large one for civil aircraft at that time. Such an aspect ratio wing can produce less induced drag compared to a lower aspect ratio wing. This means that Electra's wing was able to produce more lift for a given amount of drag, improving its overall aerodynamic efficiency. This, in turn, can result in improved fuel efficiency and range, which would have been important considerations for Electra's mission profile. Also, Electra was designed as a twin-engine monoplane, which can be prone to instability due to engine torque and other factors. The higher aspect ratio wing of the Electra can provide greater inherent stability. |
| Positive (3$^\circ$) wing dihedral                   | Improve lateral stability<br />Improve control during landing and takeoff<br />Improve roll response | The dihedral angle creates a rolling moment that helps stabilize the aircraft in flight, reducing the risk of unintended roll or bank angles. This can be particularly important during takeoff and landing when the aircraft is most vulnerable to unwanted movements.  Also, the dihedral angle can increase the lift produced by the wings, improving the aircraft's performance during takeoff and landing. This can reduce the amount of runway needed for takeoff and landing and allow the aircraft to operate from shorter runways. And this additional lift can improve the aircraft's performance in crosswind situations by producing by acting to counteract the sideways force of the wind. This can help the aircraft maintain its desired heading during crosswind landings. |
| None wing sweep                                      | /                                                            | The Lockheed Model 10 Electra was designed and built in the 1930s, before the concept of wing sweep was fully understood and before it became a common feature of aircraft design. |
| Wing incidence (detail values are given below)       | Improve lift distribution<br />Improve stall characteristics<br />Improve roll response | The different incidences at the root and tip of the wings can help improve the lift distribution across the entire wingspan of the aircraft. The root incidence of zero degrees provides a neutral or zero-lift angle of attack, while the 2-degree incidence at the wingtip creates a more favorable angle of attack for generating lift. This results in a more efficient lift distribution that can improve the aircraft's performance. The different incidences at the root and tip of the wings can also help improve the aircraft's stall characteristics. The zero-degree incidence at the root can help prevent the root section of the wing from stalling before the wingtips, which can lead to a more gradual stall and better control of the aircraft. The different incidences at the root and tip of the wings can improve the aircraft's roll response. The wingtip with a higher angle of incidence generates more lift than the root section, which can cause the aircraft to roll in the desired direction when the ailerons are deflected. This can make the aircraft more responsive and easier to control during maneuvers, such as turns and banking. Additionally, the use of different incidences can improve the aircraft's ability to recover from a bank or roll induced by turbulence or other external factors, providing greater stability and safety for the aircraft and its occupants. |
| Wing airfoil section (detail values are given below) | Improved low and high-speed performance<br />Preventing tip stall | The thicker NACA2213 airfoil at the root provides greater lift, allowing the aircraft to take off and land more easily and safely, while the thinner NACA2206 airfoil at the tip reduces drag and improves high-speed performance, allowing the aircraft to fly more efficiently at cruising altitude. The combination of airfoils helps prevent the wing from stalling at the tip first, which can lead to loss of control and potentially dangerous situations. |



### Graphic

![3 views of the wing of Lockheed Model 10 Electra](C:\Users\hanse\OneDrive - sjtu.edu.cn\Aircraft Engineering\3 views.jpg)

Dimensionless parameters are also listed in the table below:

| Dimensionless parameter  | Value                             |
| ------------------------ | --------------------------------- |
| Aspect Ratio (AR)        | 7.2                               |
| Wing sweep               | None                              |
| Thickness-to-chord Ratio | 13%@root                          |
| Wing Dihedral            | 3$^\circ$                         |
| Wing Incidence           | 0$^\circ$@root<br />2$^\circ$@tip |
| Wing Airfoil Section     | NACA 2213@root<br />NACA 2206@tip |
