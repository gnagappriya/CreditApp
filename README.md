Rest - H2 - JUnit

1. Credit Decision Engine.

2. POM File Structure.

<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
		</dependency>
		
		<dependency>
			<groupId>com.h2database</groupId>
			<artifactId>h2</artifactId>
			<scope>runtime</scope>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
			<exclusions>
				<exclusion>
					<groupId>junit</groupId>
					<artifactId>junit</artifactId>
				</exclusion>
			</exclusions>
		</dependency>
		<dependency>
			<groupId>org.junit.jupiter</groupId>
			<artifactId>junit-jupiter-api</artifactId>
			<scope>test</scope>
		</dependency>
		<dependency>
			<groupId>org.junit.jupiter</groupId>
			<artifactId>junit-jupiter-engine</artifactId>
			<scope>test</scope>
		</dependency>
	</dependencies>
  
  
3. JUnit Coverage.


![image](https://user-images.githubusercontent.com/36439883/117083032-55ed9a80-ad61-11eb-8f06-7de9676d2938.png)


![image](https://user-images.githubusercontent.com/36439883/117082968-2fc7fa80-ad61-11eb-84e2-b06aaeb4559a.png)

4. Test Results

Save a SSN number:

![image](https://user-images.githubusercontent.com/36439883/117083362-2ab77b00-ad62-11eb-87a5-72bfa2f7d333.png)

Get the Results:

![image](https://user-images.githubusercontent.com/36439883/117083403-402ca500-ad62-11eb-9ac7-59497b80b51c.png)

Get the SSN:

![image](https://user-images.githubusercontent.com/36439883/117083478-6a7e6280-ad62-11eb-8653-95505bd930ef.png)



