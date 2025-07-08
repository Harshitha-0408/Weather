
# Simulated user input (change these values as needed)
temperature = 15  # Example: temperature in Celsius
description = "cloudy"  # Example: description like 'clear', 'rain', etc.

# Determine the weather type and assign to variable 'a'
if "rain" in description.lower():
    a = "Rainy"
elif temperature < 18:
    a = "Cold"
elif "clear" in description.lower() or "sunny" in description.lower():
    a = "Sunny"
else:
    a = "Moderate"

# Output
print(f"Temperature: {temperature}°C")
print(f"Weather Description: {description}")
print(f"Detected Weather Type (a): {a}")
