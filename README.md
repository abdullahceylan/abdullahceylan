```js
const About = ({ who = 'Abdullah Ceylan' }) => (
    <>
      <Summary>
        {who}
        Frontend Developer.
        Proficient in web technologies such as JavaScript, GraphQL, React.js, React Native.
      </Summary>
      <Workplace
        data={{
          company: 'Creativouse',
          role: 'Senior Frontend Developer'
        }}
      />
      <Highlights
        data={[
          'JavaScript', 'React.js', 'Next.js', 'React Native', 'Node.js',
          'GraphQL', 'Docker / Jenkins', 'AWS', 'Git', 'SASS'
        ]}
      />
    </>
  );

export default AboutMe;
```
