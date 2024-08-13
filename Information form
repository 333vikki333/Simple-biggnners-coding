import streamlit as st

def main ():
    st.title('Examination form')

    name = st.text_input("Enter Your Full Name")
    roll_number = st.text_input('Enter Your roll Number')
    father_name = st.text_input('Enter Your Father Name')
    mother_name = st.text_input('Enter Your Mother Name')
    email = st.text_input("Enter Your Email Address")
    exam_date = st.date_input("Exam date")
    gender = st.selectbox('Select Your gender',['Male , Female , other'])
    age = st.number_input('Enter your age', min_value=18,max_value=40)
    photo = st.file_uploader('Upload your Photo',type=['jpg,jpeg,png'])
    signature = st.file_uploader('Upload your Signature',type=['jpg,jpeg,png'])



    agree_terms = st.checkbox('I agree to the terms and condition')

    if st.button('Submit'):
        if agree_terms:
            st.success(f'Name:{name}')
            st.success(f'Roll Numer:{roll_number}')
            st.success(f'Email: {email}')
            st.success(f'Age:{age}')
            st.success(f'Gender:{gender}')
            st.success(f'Exam_date:{exam_date}')
            st.success(f'Photo:{photo}')
            st.success(f'Siganture:{signature}')
            st.success(f'Father Name:{father_name}')
            st.success(f'Mother Name:{mother_name}')
            st.success('registration successful, best of luck')
        else:
            st.error('information error,please enter correct information or Please agree to the terms and condition')


if __name__ == '__main__':
    main()




