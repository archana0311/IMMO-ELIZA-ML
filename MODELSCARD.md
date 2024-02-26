Model card

Project context



Short recap of the project context.

Data

Input dataset- Target variables and features

Target variable:Price

Features:

num_features = ["primary_energy_consumption_sqm","garden_sqm", "cadastral_income", "latitude", "longitude", "Age_of_building", "total_area_sqm", "surface_land_sqm", "nbr_frontages", "nbr_bedrooms", "terrace_sqm"  ]
    fl_features = ["fl_terrace", "fl_floodzone", "fl_swimming_pool", "fl_floodzone","fl_double_glazing" ]
    cat_features = ['property_type', 'subproperty_type', 'region','province', 'locality','state_building','epc', 'heating_type',]


Model details

Missing values in quantitaive data replaced by the mean

Categorical variables with one-hot encoding using OneHotEncoder

Models tested, final model chosen, ...

Performance

Performance metrics for the various models tested, visualizations, ...



Limitations

What are the limitations of your model?

## Usage

What are the dependencies, what scripts are there to train the model, how to generate predictions, ...

## Maintainers

Who to contact in case of questions or issues?