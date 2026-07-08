import streamlit as st
st.title("interactive streamlit app")
name=st.text_input("enter your name")
if st.button('submit'):
    st.write("hello,{name}! welcome to streamlit")
