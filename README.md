##  Delta to Star & Star to Delta Transformations

This program allows you to transform electrical resistance configurations between Delta (Δ) and Star (Y) forms. Follow the instructions below to use the program effectively.

## Main Interface

When you open the program, the main interface provides three options:

- **Left Button**: Transform from Delta to Y.
- **Right Button**: Transform from Y to Delta.
- **Quit Button**: Exit the program at any time.

![image](https://github.com/karimmahmoud22/Star-Delta-Transformation/assets/82693464/c2d0ded8-5317-4894-bdcb-5c238a98c28a)


## Delta to Star Interface

Clicking the left button (Delta to Star) will take you to an interface for transforming Delta configurations to Star configurations.

### Instructions

1. **Enter Values**: Input the values of the three resistances \( R_{12} \), \( R_{23} \), and \( R_{31} \) in Delta form.
2. **Transform**: Click on the "Transform" button.
3. **Result**: The corresponding resistances in Y form will appear below the transform button.

To perform another transformation, simply enter new Delta values and click the "Transform" button again. There is no need to return to the main interface.

![image](https://github.com/karimmahmoud22/Star-Delta-Transformation/assets/82693464/651a53bb-c300-4c93-97c0-bfc6d158c437)

## Star to Delta Interface

Clicking the right button (Star to Delta) will take you to an interface for transforming Star configurations to Delta configurations.

![image](https://github.com/karimmahmoud22/Star-Delta-Transformation/assets/82693464/bfe6d198-df25-48b3-a09a-ea2e4b987ecd)

### Instructions

1. **Enter Values**: Input the values of the three resistances \( R_1 \), \( R_2 \), and \( R_3 \) in Star form.
2. **Transform**: Click on the "Transform" button.
3. **Result**: The corresponding resistances in Delta form will appear.

For additional transformations, follow the same steps without returning to the main interface.

## Notes

### Delta to Star Transformations

- \( R_1 = \frac{R_{12} \cdot R_{31}}{R_{12} + R_{23} + R_{31}} \)
- \( R_2 = \frac{R_{12} \cdot R_{23}}{R_{12} + R_{23} + R_{31}} \)
- \( R_3 = \frac{R_{23} \cdot R_{31}}{R_{12} + R_{23} + R_{31}} \)

### Star to Delta Transformations

- \( R_1 = (R_{12} + R_{23}) + \frac{R_{12} \cdot R_{23}}{R_{31}} \)
- \( R_2 = (R_{31} + R_{23}) + \frac{R_{31} \cdot R_{23}}{R_{12}} \)
- \( R_3 = (R_{31} + R_{12}) + \frac{R_{31} \cdot R_{12}}{R_{23}} \)

Make sure to enter the values of the resistances in the correct form to obtain accurate results.
