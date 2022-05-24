Navigation -> move from one screen to another

stack
package: react-navigation-stack  
Module/class :
method : createStackNavigator()

components or screens

tab -> name = ""  component=""




npm install -g yarn

 yarn add @react-navigation/stack
 yarn add @react-navigation/native

expo install react-native-gesture-handler
expo install react-native-reanimated
expo install react-native-screens
expo install react-native-safe-area-context
expo install @react-native-community/masked-view




return (
      <NavigationContainer>
      <Stack.Navigator initialRouteName="Home" screenOptions={{
        headerShown: false
      }}>
        <Stack.Screen name="Home" component={HomeScreen} />
        <Stack.Screen name="IssLocation" component={IssLocation} />
        <Stack.Screen name="Meteors" component={Metor} />
      </Stack.Navigator>
    </NavigationContainer>  
    );