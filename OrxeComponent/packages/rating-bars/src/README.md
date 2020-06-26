# orxe-rating-bars

# USAGE: 
  <orxe-rating-bars 
  title="Business"
  label="Very Good"
  rating="78"
  conversionRate="10"
  ></orxe-rating-bars>

# PROPERTIES
    rating: Number >= 0. Responsible for color as well as aria label.
    label: String for label on bottom left
    conversionRate - Rate of conversion (Used for rating / conversion Rate) ex: ( 75 / 10 ) = 7.5
    a11yLabel - Aria label for Screen Readers if not provide components creates it dynamically. ex: Bussiness 7.1 out of 10

# CSS PROPERTIES
    --orxe-bar-shell-color: var(--tertiary);
    --orxe-bar-shell-padding: 2px;
    --orxe-bar-shell-margin-bottom: 2px;
    --orxe-bar-shell-border-radius:50px;

    --orxe-bar-progress-color: var(--primary);
    --orxe-bar-progress-height:20px;

    --orxe-bar-label-color: var(--tertiary);
    --orxe-bar-label-font-family: var(--primary-font-family);

    --orxe-progress-color-poor:red;
    --orxe-progress-color-normal:orange;
    --orxe-progress-color-good:yellow;
    --orxe-progress-color-excellent:green;
    --orxe-progress-color-awesome:darkgreen;
    
# ADDITIONAL INFO
    Test cases and story book yet to be added. (Under-progress)
