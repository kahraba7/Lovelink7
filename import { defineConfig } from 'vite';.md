import { defineConfig } from 'vite';  
import react from '@vitejs/plugin-react';  
  
export default defineConfig({  
  plugins: [react()],  
  base: './', // يضمن عمل الروابط بشكل صحيح عند رفع الموقع  
  server: {  
    port: 3000,  
  },  
});  
