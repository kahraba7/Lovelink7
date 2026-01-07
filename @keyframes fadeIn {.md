@keyframes fadeIn {  
  from { opacity: 0; transform: translateY(20px); }  
  to { opacity: 1; transform: translateY(0); }  
}  
  
.animate-fade-in {  
  animation: fadeIn 1.2s ease-out forwards;  
}  
  
::selection {  
  background: #1a1a1a;  
  color: #ffffff;  
}  
  
html {  
  scroll-behavior: smooth;  
}  
  
/* Custom transitions for a luxury feel */  
.transition-luxury {  
  transition: all 0.6s cubic-bezier(0.16, 1, 0.3, 1);  
}  
