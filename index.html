import React, { useState, useEffect } from 'react';
import { View, Text, StyleSheet, ImageBackground, TouchableOpacity, Dimensions, Animated, Platform } from 'react-native';
import { BlurView } from 'expo-blur';

const { width, height } = Dimensions.get('window');

export default function AuraForgeMaster() {
  const [isLocked, setIsLocked] = useState(true);
  const glowAnim = new Animated.Value(1);

  useEffect(() => {
    Animated.loop(
      Animated.sequence([
        Animated.timing(glowAnim, { toValue: 1.1, duration: 2500, useNativeDriver: true }),
        Animated.timing(glowAnim, { toValue: 1, duration: 2500, useNativeDriver: true }),
      ])
    ).start();
  }, []);

  return (
    <View style={styles.container}>
      <ImageBackground 
        source={{ uri: 'https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe' }} 
        style={styles.background}
      >
        <View style={styles.overlay}>
          {isLocked ? (
            <View style={styles.centered}>
              <Animated.View style={{ transform: [{ scale: glowAnim }] }}>
                <View style={styles.lockCircle}>
                  <Text style={styles.lockIcon}>✨</Text>
                </View>
              </Animated.View>
              <Text style={styles.title}>AURAFORGE</Text>
              <Text style={styles.subtitle}>LUXURY SANCTUM</Text>
              <TouchableOpacity onPress={() => setIsLocked(false)} style={styles.divineButton}>
                <Text style={styles.buttonText}>IGNITE SOUL</Text>
              </TouchableOpacity>
            </View>
          ) : (
            <View style={styles.dashboard}>
              <Text style={styles.headerTitle}>System Active</Text>
              <View style={styles.dataCard}>
                <Text style={styles.cardLabel}>Vault Status</Text>
                <Text style={styles.cardValue}>Synchronized with GitHub</Text>
              </View>
              <TouchableOpacity onPress={() => setIsLocked(true)} style={styles.logoutBtn}>
                <Text style={styles.logoutText}>Secure Vault</Text>
              </TouchableOpacity>
            </View>
          )}
        </View>
      </ImageBackground>
    </View>
  );
}

const styles = StyleSheet.create({
  container: { flex: 1, backgroundColor: '#000' },
  background: { flex: 1 },
  overlay: { flex: 1, backgroundColor: 'rgba(0,0,0,0.8)', padding: 30 },
  centered: { flex: 1, justifyContent: 'center', alignItems: 'center' },
  lockCircle: { width: 100, height: 100, borderRadius: 50, justifyContent: 'center', alignItems: 'center', borderWidth: 1, borderColor: '#fff' },
  lockIcon: { fontSize: 40 },
  title: { color: '#fff', fontSize: 32, fontWeight: '200', letterSpacing: 8, marginTop: 40 },
  subtitle: { color: 'rgba(255,255,255,0.4)', fontSize: 12, letterSpacing: 4, marginTop: 10 },
  divineButton: { marginTop: 60, paddingHorizontal: 40, paddingVertical: 15, borderRadius: 30, borderWidth: 1, borderColor: '#fff' },
  buttonText: { color: '#fff', letterSpacing: 2, fontSize: 14 },
  dashboard: { flex: 1, paddingTop: 60 },
  headerTitle: { color: '#fff', fontSize: 24, fontWeight: '300' },
  dataCard: { marginTop: 40, padding: 25, borderRadius: 20, backgroundColor: 'rgba(255,255,255,0.05)', borderWidth: 1, borderColor: 'rgba(255,255,255,0.1)' },
  cardLabel: { color: 'rgba(255,255,255,0.4)', fontSize: 10, textTransform: 'uppercase' },
  cardValue: { color: '#fff', fontSize: 18, marginTop: 8 },
  logoutBtn: { position: 'absolute', bottom: 40, alignSelf: 'center' },
  logoutText: { color: 'rgba(255,255,255,0.3)', fontSize: 10, textTransform: 'uppercase' }
});
