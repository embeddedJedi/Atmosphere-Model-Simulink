# Atmosphere-Model-Simulink

The atmosphere model is used in rocket flight simulations to predict the conditions the rocket will encounter as it passes through the atmosphere. This model is critical to validate the rocket's design and flight planning, optimize its performance and improve its safety. Using this model, rocket engineers calculate variables such as temperature, pressure and density as the rocket passes through different layers of the atmosphere during ascent. Thus, factors such as resistance and thrust that the rocket may encounter during flight are more accurately predicted.

In the designed Atmosphere Model, air density, pressure, temperature and speed of sound data are obtained depending on the altitude. All of the calculations used in this model are given below.

# 1. Temperature:

![image](https://github.com/user-attachments/assets/e9fc1aea-211f-43b6-81c9-c4daf89607dc)

Hb : is the basic geopotential altitude

Tb : is the base temperature,

Lb : is the basic temperature lapse rate

# 2. Pressure:

![image](https://github.com/user-attachments/assets/700092ae-0010-42b8-a9f1-52c8ed9dfc02)

P_b : Sea level pressure value

Tb : The base temperature of layer b in K

g_0 : gravitational acceleration (9.801m/s2)

M : 0.0289644 kg/mol, the molar mass of Earth's air.

R* : 8.31432-10³ N m kmol-¹ K-¹ is the universal gas constant

TM : is the molecular scale temperature at altitude H defined above:

# 3. Air Density:

![image](https://github.com/user-attachments/assets/12787bee-7bf0-4a16-b830-20a05938fa5f)

# 4. Speed of Sound

![image](https://github.com/user-attachments/assets/ae3021e6-e5b3-478d-bf7e-15d9ea7f5ef2)

