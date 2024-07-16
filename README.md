# sky
def determine_sky_color(time_of_day):
    time_of_day = time_of_day.lower()
    
    if time_of_day == "morning":
        return "Blue with hints of orange near the horizon"
    elif time_of_day == "day":
        return "Mostly blue with occasional white clouds"
    elif time_of_day == "evening":
        return "Orange and red hues with patches of blue"
    elif time_of_day == "night":
        return "Dark with scattered stars and possibly moonlit"
    else:
        return "It's hard to tell without more specific information."

# Example usage
current_time = "day"
sky_color = determine_sky_color(current_time)
print(f"The current sky color is: {sky_color}")
