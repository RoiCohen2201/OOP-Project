### Weather Station App README

#### Description
This C# console-based Weather Station App manages a virtual weather station, enabling the creation and management of temperature and humidity sensors. It features serialization for data persistence and event-driven programming to handle sensor changes.

#### Features
- Manage temperature and humidity sensors with unique IDs.
- Add/remove sensors dynamically.
- Serialize and deserialize station data using a binary formatter.
- Validate sensor data with custom logic.
- Events triggered on sensor addition/removal.

#### Usage
1. Clone the repository.
2. Open with Visual Studio.
3. Execute `Program.cs` and use the console menu to interact with the application.

#### How to Contribute
- Fork the repository.
- Create a new branch for your features.
- Make your changes and test them.
- Submit a pull request with a clear list of what you've done.

#### Code Example
```csharp
// Adding a new temperature sensor to the station
var station = new StationClass(1, "Main Station", "City Center");
station.AddSensor(new TemperatureSensorClass(101, "Outdoor Temp", "C", 15.5));
```
