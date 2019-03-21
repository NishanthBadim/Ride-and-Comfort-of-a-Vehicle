WFT_SUV_City1_R1_ The dataset which contains the data of the car travelled on the city roads it contain of 23 features and 657172 rows.

The below are the column description of the dataset

Refernce time series data for Vehicle: Mahindra Scorpio (2007 Model) -- Variant : 2.6LX 2WD 7STR BS/III Chan	Y Title Description

Veh_Speed	Vehicle Speed in m/s
CS_RR	Rear right side Coil Spring's measured Strain in microstrain
CS_RL	Rear left side Coil Spring's measured Strain in microstrain
ARB_R	Rear side Anti-roll Bar's measured Strain in microstrain
AXLE_RR_Z	Axle's Rear right side measured Strain in microstrain
AXLE_RL_Z	Axle's Rear left side measured Strain in microstrain
RR_Mz	Wheel moment (N.m) about Z direction measured at Rear right wheel's center (Spindle location)
RR_My	Wheel moment (N.m) about Y direction measured at Rear right wheel's center (Spindle location)
RR_Mx	Wheel moment (N.m) about X direction measured at Rear right wheel's center (Spindle location)
RR_Fz	Wheel force (N) in Z direction measured at Rear right wheel's center (Spindle location)
RR_Fy	Wheel force (N) in Y direction measured at Rear right wheel's center (Spindle location)
RR_Fx	Wheel force (N) in X direction measured at Rear right wheel's center (Spindle location)
RL_Mz	Wheel moment (N.m) about Z direction measured at Rear Left wheel's center (Spindle location)
RL_My	Wheel moment (N.m) about Y direction measured at Rear Left wheel's center (Spindle location)
RL_Mx	Wheel moment (N.m) about X direction measured at Rear Left wheel's center (Spindle location)
RL_Fz	Wheel force (N) in Z direction measured at Rear Left wheel's center (Spindle location)
RL_Fy	Wheel force (N) in Y direction measured at Rear Left wheel's center (Spindle location)
RL_Fx	Wheel force (N) in X direction measured at Rear Left wheel's center (Spindle location)
RRA_Z	Axle's Rear right side measured Acceleration in g (9.81xm/s^2)
RLA_Z	Axle's Rear left side measured Acceleration in g (9.81xm/s^2)
CG_X	Center of Gravity location's X direction measured Acceleration in g (9.81xm/s^2)
CG_Y	Center of Gravity location's Y direction measured Acceleration in g (9.81xm/s^2)
CG_Z	Center of Gravity location's Z direction measured Acceleration in g (9.81xm/s^2)
In the WFT_SUV_City1_R1_ dataset there are correlation between various columns 1.RL_Fx is highly correlated with RR_FX(P=0.91659) 2.RL_FY is highly correlated with RL_MX(p=0.92426) 3.RL_MX is highly correlated with RR_FY(p=0.93024) 4.RL_MY is highly correlated with RR_MY(p=0.99482) using PCA(principal component analysis the the two highly correlated columns are combined and made a single column) As the data is unlabled so it is unsupervised data so we must apply unsuperised algorithm. we applied KMEANS clustering for the available data and labled in to two clusters comfort and uncomfort. And we also rated the comfortness and uncomfortness of the vechile from the scale 0-10 by considering the the distance form centroid to that particular point in that cluster.

WFT_SUV_EX_R1_ The dataset which contains the data of the car travelled on the express roads it also contains 23 features and 1048570 It also contains the same column description of the above dataset. In the WFT_SUV_EX_R1_ dataset there are correlation between various columns 1.RL_Fy is highly correlated with RL_MX(P=0.90216) 2.RL_MX is highly correlated with RR_MX(p=0.93048) 3.RL_MY is highly correlated with RR_MY(p=0.98586) using PCA(principal component analysis the the two highly correlated columns are combined and made a single column) As the data is unlabled so it is unsupervised data so we must apply unsuperised algorithm. we applied KMEANS clustering for the available data and labled in to two clusters comfort and uncomfort. And we also rated the comfortness and uncomfortness of the vechile from the scale 0-10 by considering the the distance form centroid to that particular point in that cluster.

WFT_SUV_RR1_R1_ The dataset conatins the data of the car travelled on the RR roads it also contain 23 features and 146198 It also contains the same column description of the above dataset. In the WFT_SUV_RR1_R1_ dataset there are correlation between various columns 1.RL_My is highly correlated with RR_My(P=0.99193) using PCA(principal component analysis the the two highly correlated columns are combined and made a single column) As the data is unlabled so it is unsupervised data so we must apply unsuperised algorithm. we applied KMEANS clustering for the available data and labled in to two clusters comfort and uncomfort. And we also rated the comfortness and uncomfortness of the vechile from the scale 0-10 by considering the the distance form centroid to that particular point in that cluster.
